# ForceGL4.0
- A modified version of [ForceGL2.0](https://github.com/coredex-source/ForceGL2.0-1.2x) which instead of changing GLFW hints to work with OpenGL 2.0 changes them to work with OpenGL 4.0.
- A Minecraft mod for [Fabric](https://fabricmc.net/), [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), [Quilt](https://quiltmc.org/) & [NeoForge](https://neoforged.net) that forces the game to use OpenGL 3.0.
- You can download it using [CurseForge](https://www.curseforge.com/), [Modrinth](https://modrinth.com/).


## Fixes-
- Fixes driver crash with old GPUs caused by Java exception while loading shaders using Iris or Oculus. (Including the one's which can run Minecraft without the mod.) [Untested for ForceGL4.0, works on [ForceGL2.0](https://github.com/coredex-source/ForceGL2.0-1.2x)]

## Why?
- Uh just cause why not ?

## But does it work?
- As far as I tested, there have been no issues.

## I found an issue!
- Open an issue in the issues tab on Github.

## Compiling the mod
- If you want to compile ForceGL3.0 by yourself, use the following command:
```
./gradle build  
```
- Use the build from {LoaderType}/build/libs.

## Have an older graphics card ?
- Use [ForceGL2.0](https://github.com/coredex-source/ForceGL2.0-1.2x)
