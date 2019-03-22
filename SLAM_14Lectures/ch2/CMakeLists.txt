# claim the required cmake version
cmake_minimum_required( VERSION 2.8 )

# claim a cmake project
project( HelloSLAM )

# addd a executable program
# gramma: add_executable( program name    source code file)
add_executable( helloSLAM helloSLAM.cpp)

# add a library
add_library( hello libHelloSLAM.cpp)

# add a share library
add_library( hello_shared SHARED libHelloSLAM.cpp)
