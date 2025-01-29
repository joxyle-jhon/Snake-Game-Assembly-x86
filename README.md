# Snake Game using Assembly x86 (MIPS)

## Introduction

This is a version of classic snake game for MIPS processor written in Assembly.

## Setup Mars IDE

To run the `.asm` file you can download a MIPS emulator. The MIPS Mars is
a free emulator made in java that you can download [here](http://courses.missouristate.edu/KenVollmar/mars/).
The actual project file is `mips_snake.asm`. Everything else in `tests` folder as its name sugests is just a bunch of tests For
handling input, generating random numbers and so on.

## Running on Mars 

Setting the enviroment to run the game:

![settings](imgs/settings.gif)

It dies when hits itself...

![self collinsion](imgs/self-collision.gif)

... Or the walls.

![walls collision](imgs/wall-collision.gif)
