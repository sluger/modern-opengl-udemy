# modern-opengl-udemy

This repo is based on https://github.com/sluger/modern-opengl-starter and serves as a playground for the udemy course on Computer Graphics with Modern OpenGL and C++ by Ben Cook.

## Prerequisites

- [https://cmake.org/](cmake), e.g. via Homebrew at https://formulae.brew.sh/formula/cmake
- clang, e.g. via `xcode-select --install` on MacOS
- Set up IDE of choice, e.g. see the VS Code guide: https://code.visualstudio.com/docs/cpp/config-clang-mac)

Also recommending the cpp and cmake VS Code extensions.

## Install

```
git clone git@github.com:sluger/modern-opengl-udemy.git
cd modern-opengl
mkdir build
cd build
cmake ..
make -j
```

## Run the application

```
./modern-opengl
```
