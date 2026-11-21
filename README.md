# TopDownAdventure Focal Engine Project

I created this Focal Engine project using resources from the [Top-Down Action Adventure Starter Kit](https://github.com/Nodragem/top-down-action-adventure-starter-kit) by Nodragem, a Godot 4 project built from KayKit assets.

## Credits

All content comes from CC0 1.0 sources:

- **Levels, characters (Icy, Dr. Megadroon, the enemy minion), laboratory objects, switches and doors:** [Top-Down Action Adventure Starter Kit](https://github.com/Nodragem/top-down-action-adventure-starter-kit) by Nodragem.
- **Building kit, props and rocks:** [KayKit Prototype Bits](https://kaylousberg.itch.io/prototype-bits) and [KayKit Space Base Bits](https://kaylousberg.itch.io/space-base-bits) by Kay Lousberg ([kaylousberg.com](https://www.kaylousberg.com)).

## What works now

This is a quick port of the original scene, not a working game yet. Only walking, jumping and the camera are ported, so for now Level1 is mostly a static scene to walk around in.
In Level1, press Play in the editor.

| Key | Action |
|---|---|
| W, A, S, D | Move, relative to the camera |
| Space | Jump |
| Q / E (or 1 / 3, as in the starter kit) | Turn the camera |

The player walks through walls and props, because there is no wall collision. It stays on the highest floor below it, walks up and down stairs, and falls off edges. If it falls 30 m below its start, it is put back at the start.