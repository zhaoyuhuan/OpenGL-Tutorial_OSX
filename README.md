<h1>Build OpenGL 3.2 from Command Line on OSX</h1>

<b>These example files are based on the example files v0009_21 found at <a href="http://http://www.opengl-tutorial.org">opengl-tutorials.org</a>.</b> 
* I created custom makefiles for each tutorial so that xcode and CMake are not required
* Altered the headings in the source code for these to compile with the makefiles. 
* The rest of the files are the same as the ones used in the tutorial.
* tutorial number 17 is currently not linked correctly. 1-16 should all work

How to compile these examples form command line on OSX (For the Noob):
1) git clone this repository to your hardrive
1) Download XCode and command line tools  (Xcode preferences/downloads/ command line tools download)
2) Install homebrew:  http://mxcl.github.com/homebrew/
3) In the Terminal run:  brew install pkgconfig
4) then:  brew install glfw
5) brew install glew
6) cd tutorialWorkingDirectory and run:    make      
7) ./nameOfNewlyCompiledProgram


* Do whatever you want with these files, as noted at opengl-tutorials.org

* Be sure to check out the kinect DJ-ing open source project <a href="https://github.com/3dj">3DJ</a>
