P=tutorial06
OBJECTS= shader.o texture.o controls.o
DEBUG= -g
CFLAGS= $(DEBUG) -Wall -O3 `pkg-config --cflags libglfw` `pkg-config --cflags glew`
LDLIBS= -framework OpenGL `pkg-config --libs glew` `pkg-config --libs libglfw`
CC=clang

$(P): $(OBJECTS) 

all: shader.o $(P)

shader.o: shader.cpp shader.hpp 
	clang -c -g -Wall -O3 shader.cpp

texture.o: texture.cpp texture.hpp
	clang -c -g -Wall -O3 texture.cpp

controls.o: controls.cpp controls.hpp
	clang -c -g -Wall -O3 controls.cpp

clean:
	\rm *.o *~ $(P)

tar:
	tar cfv $(P).tar tutorial02.cpp shader.cpp shader.hpp
