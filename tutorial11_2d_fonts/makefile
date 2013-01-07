P=tutorial11
OBJECTS= shader.o texture.o controls.o objloader.o vboindexer.o text2d.o
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

objloader.o: objloader.cpp objloader.hpp
	clang -c -g -Wall -O3 objloader.cpp

vboindexer.o: vboindexer.cpp vboindexer.hpp
	clang -c -g -Wall -O3 vboindexer.cpp

text2d.o: text2d.cpp text2d.hpp
	clang -c -g -Wall -O3 text2d.cpp
	 
clean:
	\rm *.o *~ $(P)

tar:
	tar cfv $(P).tar tutorial02.cpp shader.cpp shader.hpp
