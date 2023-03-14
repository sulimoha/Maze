Problem:
root@2c94e78603ff:~/SDL/Maze/src# ./01_hello_SDL
./01_hello_SDL: error while loading shared libraries: libSDL2-2.0.so.0: cannot open shared object file: No such file or directory

Solution :
root@2c94e78603ff:~/SDL/Maze/src# export LD_LIBRARY_PATH="/root/SDL/build/.libs/"

Reference:
c++ - libSDL2-2.0.so.0: cannot open shared object file - Stack Overflow

g++ 01_hello_SDL.cpp -w -lSDL2 -o 01_hello_SDL

"/home/mohamed/Maze/SDL/include/SDL.h"

g ++ 03_event_driven_programming.cpp      -w -lSDL2 -o 03_event_driven_programming

/home/mohamed/Maze/05_optimized_surface_loading_and_soft_stretching


g++ 06_extension_libraries_and_loading_other_image_formats.cpp -w -lSDL2 -lSDL2_image -o 06_extension_libraries_and_loading_other_image_formats

/home/mohamed/Maze/SDL_image-release-2.6.3/SDL_image.h