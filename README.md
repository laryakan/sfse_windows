# sfse_windows
Pre-compiled version of Starfield Script Extender for Windows 11 Miscrosoft Store Version (or Gamepass).

The repository will store pre-compiled SFSE Version for GamePass Starfield Version. Please refer to [Starfield HEX Updater](https://github.com/gazzamc/starfield_hex_updater) documentation for more info.

Thanks to [CommonLibSF](https://github.com/Starfield-Reverse-Engineering/CommonLibSF) for telling me which cmake and build tools version to use to compile.

## To recompile
Use [Starfield HEX Updater](https://github.com/gazzamc/starfield_hex_updater)

### Prerequesite
Install [Chocolatey](https://chocolatey.org/)

HEX Updated will ask you to install Python Standalone, say yes
```
choco install cmake --version=3.30.8 --installargs 'ADD_CMAKE_TO_PATH=System'
choco install visualstudio2022buildtools --params "--add Microsoft.VisualStudio.Component.VC.Llvm.Clang --add Microsoft.VisualStudio.Component.VC.Llvm.ClangToolset --add Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Llvm.Clang --add Microsoft.VisualStudio.Component.VC.CMake.Project"
choco install git
```
After that, **run.bat** should work properly IF Execution Policy is set to Unrestricted (or AllSigned eventually)

You may still need to unlock the game files (or maybe not, since the Creations Update has moved a lot of game files somewhere they are reachable)
