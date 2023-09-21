# The Maze Game Project

The Maze is a Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in `C` ussing `SDL2` library. Deveploment was performed using `Ubuntu 16.04 LTS` - gcc (Ubuntu 4.8.4-2ubuntu1~16.04) 4.8.4

### About SDL2 

`Simple DirectMedia Layer` is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via `OpenGL` and `Direct3D`. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git@github.com:Mapoma2021/The-Maze-Project.git
```
## Usage 
* Use up and down arrow keys to move forward and backward (keys `w` and `s` serve the same function)
* Use right and left arrow keys to turn the camera arround (keys `d` and `a` serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze sdl2-config --cflags sdl2-config --libs;
```
## Running
After successfully compiling run the program using following command:

```bash
./maze MAP
```
where ```MAP``` is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.


## Author
Mapoma Martin [@Mapomamartin](https://github.com/Mapoma2021) <mapomamartin@gmail.com>
