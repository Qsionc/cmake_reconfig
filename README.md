# `cmake_reconfigure`

Simple CMake Reconfiguration python script that simply deletes `CMakeCache.txt` in target build directory before it reconfigures cmake.

Pass all the normal cmake arguments to this program, it passes them on to called cmake.

## `usage`

Use it as normal cmake.

If there is no `.` or `..` present on command line argument list, it will assume current working directory as build dir and search for cmake lists as normal cmake would.

