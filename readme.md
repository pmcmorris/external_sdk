External Libs
=============

This is a package for the external binary libraries used by my projects. 

Why? Because every lib seems to provide spotty binary support (missing x64
support, mixed C runtime linkage, etc.) and often have a unique and
incompatible build systems (even if they all use cmake, they all put the
outputs in different folders and name them differently).

Currently only supports Windows, x64, VS2015 binaries in (d, dz, z) styles.

Contains
========

	libepoxy-head(2016-12-01):	OpenGL extension manager (like GLEW but better?)
	glfw-3.2.1:					like SDL2 but better opengl support, and slimmer (just rendering)
	glm-0.9.8.3:				header only math lib
	Lua-5.3.3:					scripting tools and libs

TODO
====

I just did this manually, but ideally I'd write a script to git clone/sync
everything, build it, then "install" it all to the SDK folder.

