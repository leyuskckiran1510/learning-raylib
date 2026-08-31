# Learning Raylib easiest game setup
>> this project was bootstraped from [raySan game template](https://github.com/raysan5/raylib-game-template)
>> the below steps assume you are in your project dir, aka this readme file dir
0. You need `make` and dependencies of [raylib](https://github.com/raysan5/raylib)
1. Install Raylib as
```
git clone --depth 1  https://github.com/raysan5/raylib
make -C raylib/src
```
2. You are done start making game
3. To complie your game
```
make
```
4. To clean up 
```
make clean
```

Easiest raylib setup and on go process

## I want to install raylib once for all my other projects. How ?
0. git clone and make the project as shown in above step, 0-1 in any directory
1. open `Makefile`
2. find `RAYLIB_PATH           ?= raylib`, and change it, for example see below
    1. `RAYLIB_PATH           ?= $HOME/.opt/libs/raylib`,
    2. This assumes you have git clone the raylib inside the `$HOME/.opt/libs/`
    3. and ran `make -C raylib/src` on `$HOME/.opt/libs/`
    4. so based on this, pick your folder for global raylib installation 
    5. and update the make file as your need
 