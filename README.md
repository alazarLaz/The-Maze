# The Maze

The Maze is a game that presents a 3D maze to players, achieved through ray casting techniques that render a 2D map into a navigable 3D environment. It was developed using the SDL2 library and coded in C, with the development process conducted on Ubuntu 22.04.1 LTS and utilizing gcc version 11.3.0 (Ubuntu 11.3.0-1ubuntu1~22.04).

Project Page
https://alazarlaz.github.io/The-Maze/

Medium Article

https://medium.com/@alazar.yeh/the-maze-project-bacbce06884d

Author
Alazar Yehualashet
https://www.linkedin.com/in/alazar-yehualashet-4807b9216/

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/alazarlaz/The-Maze.git
```
## Usage 
Run the game by executing "./maze" or by typing "make run" in the terminal.
Move forward and backward in the maze using the up and down arrow keys. Alternatively, you can use the w and s keys to perform the same function.
Turn the camera around by using the right and left arrow keys. Similarly, you can use the d and a keys to rotate the camera.
## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```


## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://youtu.be/PY_Pi7YuLkQ)
