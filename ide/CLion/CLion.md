# CLion

- network: github, google (插件)

## Installation
- `sudo apt install git`
- [`sudo apt install build-essential`](https://askubuntu.com/a/1087872)
  - `cmake`, `g++`, `gcc`, `libc6-dev`, `dpkg-dev`
- jetbrains toolbox
- install CLion
  - plugins
- `File` => `Settings???` => `Build, Execution, Deployment` => `Toolchains` => `Default`

## Hello World

## Configuration
- [Configure CLion on Windows](https://www.jetbrains.com/help/clion/quick-tutorial-on-configuring-clion-on-windows.html)

## Videos
- [How to Setup CLion for C and C++ Development](https://youtu.be/HSf-GiJr1Bs)
- [Getting Started with CLion and GitHub Classroom](https://youtu.be/GD64-1D4XEg)
- [CLion 101 and Beyond](https://youtu.be/rfdqzfsCmx0)
- [Remote Development with CLion](https://youtu.be/g1zPcja3zAU)

## Issues
- [collect2: fatal error: ld terminated with signal 11](https://stackoverflow.com/a/57056485/1833118)
  > `sudo apt purge binutils`
  > `sudo apt remove make`
  > `sudo apt autoremove`
  > `sudo apt install build-essential`