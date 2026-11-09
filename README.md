# Transparent — Make Armor and Capes See-Through

Transparent 9minecraft Mod brings translucent texture rendering to armor, capes, paintings, and other game elements that normally render as solid blocks of color. In the default game, pixels with partial opacity cannot display transparency on these models. This mod changes how those specific models render so resource packs can display see-through textures cleanly. It operates entirely on your game client and requires no changes on multiplayer servers.

## What this build is

An unofficial rebuild of **Trikzon**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **LGPL-3.0-or-later**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, NeoForge |
| 26.2 | Fabric, NeoForge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/transparent-9minecraft-mod](https://www.9minecraft.net/transparent-9minecraft-mod/)

## Credits

Original work by **Trikzon**. Port and maintenance by 9Minecraft Studios. Licensed LGPL-3.0-or-later; the upstream licence text ships inside every build.
