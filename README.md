# game

Client  compile Guide.


You need Visual Studio 2010 Professional

You also need to install the compiled Boost libraries for 32bit.

https://sourceforge.net/projects/boost/files/boost-binaries/1.64.0/boost_1_64_0-msvc-10.0-32.exe/download


Use the dev version (latest) /dev

Open Project /dev/Laghaim_Client/Laghaim_2010.vcxproj

At the top Change the build to KP_Release_Game

On the left right click Laghaim_Client > Properties > C/C++ > General > Additional Include Directories,
Edit  Add a new line and add the boost_1_64_0 directory.  (c:/local/boost_1_64_0)

On the left again right click Laghaim_Client > Properties > Linker > General > Additional Include Directories, 
Edit  Add a new line and add the boost_1_64_0/lib32-msvc-10.0 directory.  (c:/local/boost_1_64_0/lib32-msvc-10.0)

On the left right click Laghaim_Engine > Properties > Configuration Properties > C/C++ > General > Additional Include Directories,
Edit  Add a new line and add the boost_1_64_0 directory.  (c:/local/boost_1_64_0)