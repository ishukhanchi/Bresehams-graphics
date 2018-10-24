# Bresenhams-graphics
Implementation of Bresenham's algortihm in OpenGL for all the eight octants.

## OpenGL (GLUT) on linux(ubuntu)<br>
 ### Installation<br>
* Install the following packages from the ubuntu repository:<br>
1. freeglut3-dev<br>
1. mesa-common-dev<br>

 ### Compiling and Linking<br>
1. You will have to use the -lglut linker option with gcc/g++ to compile a program with glut library.<br>
1. For example, to compile the program cube.c that uses GLUT type, use<br>
1. gcc -o cube cube.c -lglut -lGLU<br>
1. to get the binary executable cube.<br>

 If you are not using GLUT and want to use the lower level libraries then use -lGL -lGLU also in the linker options. 

 sudo apt-get install freeglut3 freeglut3-dev mesa-common-dev<br>

Check your /usr/include/GL folder to verify the installation of the openGL headers that you intend to use. 

## OpenGL (GLUT) on Windows
### Installation

1. opengl32.lib
1. glu32.lib
1. gl.h
1. glu.h

* These are usually provided by the manufacturer of your display adapter. The following files will also be needed for using GLUT

1. glut32.dll
1. glut32.lib
1. glut.h
1. Download GLUT. Unzip and copy glut32.dll to C:\Windows\system32 
* Note:The code given works in ubuntu.To run it in Windows, add a header file #include<windows.h>
