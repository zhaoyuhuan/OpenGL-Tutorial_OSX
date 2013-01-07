<h1>Build OpenGL 3.2 from Command Line on OSX</h1>

<b>These example files are based on the example files v0009_21 found at <a href="http://www.opengl-tutorial.org">opengl-tutorials.org</a>.</b> 
* I created custom makefiles for each tutorial so that xcode and CMake are not required
* Altered the headings in the source code for these to compile with the makefiles. 
* The rest of the files are the same as the ones used in the tutorial.
* tutorial number 17 is currently not linked correctly. 1-16 are working

<b>How to compile these examples form command line on OSX:</b>
<ol>
	<li> git clone this repository to your hardrive</li>
	<li> Download XCode and command line tools  (Xcode preferences/downloads/ command line tools download)</li>
	<li> Install homebrew:  http://mxcl.github.com/homebrew/</li>
	<li> In the Terminal run:  brew install pkgconfig</li>
	<li>  brew install glfw</li>
	<li> brew install glew</li>
	<li> cd tutorialWorkingDirectory and run:    make    </li>  
	<li> ./nameOfNewlyCompiledProgram</li>
</ol>


* Do whatever you want with these files, as noted at opengl-tutorials.org

Questions: samruberti@gmail.com
