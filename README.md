Filesystem in User Space Using FUSE
=======================================

This is an example of using FUSE to build a simple in-memory filesystem that supports creating new files and directories.
Type the Following commands in terminal: \
$ ./Compile.sh \
$ ./Mount.sh \
A directory called Proj will be created and it will contain your mounted Subdirectory SubProj. \
Now move to SubProj to create new files and write into them. \
Move back to your initial directory and type following commands to unmount SubProj and delete it: \
$ ./Unmount.sh \
$ ./DelDir.sh
