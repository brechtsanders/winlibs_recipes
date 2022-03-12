# winlibs build recipes
Recipes for natively building [winlibs](https://winlibs.com/) packages from source using the MinGW-w64 GCC compiler for Windows.

A Windows system wit a working [MSYS2](https://www.msys2.org/) shell and the [winlibs_tools](https://github.com/brechtsanders/winlibs_tools/) are needed to build these recipes.

## Goal

The primary goal of [winlibs.com](https://winlibs.com/) is to build C/C++ source code on native Windows 32-bit and 64-bit platforms using [MinGW-w64](https://www.mingw-w64.org/) [GCC](https://gcc.gnu.org/).

These recipes descripy how to build each package from source into a package that can be managed with the [winlibs_tools](https://github.com/brechtsanders/winlibs_tools/).

## Recipe Format

A `.winlib` build recipe is written as a series of shell commands that can be run manually in the [MSYS2](https://www.msys2.org/) shell.
At the same time they contain fixed commands that allow the build tools to extract information and run them in an automated and unattended way.

## License

The build recipes are distributed under the MIT license.
