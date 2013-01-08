P=playground
OBJECTS= 
DEBUG= -g
CFLAGS= $(DEBUG) -Wall -O3 `pkg-config --cflags libglfw` `pkg-config --cflags glew`
LDLIBS= -framework OpenGL `pkg-config --libs glew` `pkg-config --libs libglfw`
CC=clang

$(P): $(OBJECTS) 

clean:
	\rm *.o *~ $(P)

tar:
	tar cfv $(P).tar tutorial02.cpp shader.hpp shader.cpp
