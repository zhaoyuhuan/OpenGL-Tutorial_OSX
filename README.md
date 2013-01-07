<h1>Build OpenGL 3.2 from Command Line on OSX</h1>

<b>These example files are based on the example files v0009_21 found at <a href="http://http://www.opengl-tutorial.org">opengl-tutorials.org</a>.</b> 
* I created custom makefiles for each tutorial so that xcode and CMake are not required
* Altered the headings in the source code for these to compile with the makefiles. 
* The rest of the files are the same as the ones used in the tutorial.
* tutorial number 17 is currently not linked correctly. 1-16 should all work

<b>How to compile these examples form command line on OSX (For the Noob):</b>
<ol>
	<li>1) git clone this repository to your hardrive</li>
	<li>2) Download XCode and command line tools  (Xcode preferences/downloads/ command line tools download)</li>
	<li>3) Install homebrew:  http://mxcl.github.com/homebrew/</li>
	<li>4) In the Terminal run:  brew install pkgconfig</li>
	<li>5) then:  brew install glfw</li>
	<li>6) brew install glew</li>
	<li>7) cd tutorialWorkingDirectory and run:    make    </li>  
	<li>8) ./nameOfNewlyCompiledProgram</li>
</ol>


* Do whatever you want with these files, as noted at opengl-tutorials.org

* Be sure to check out the kinect DJ-ing open source project <a href="https://github.com/3dj">3DJ</a>
