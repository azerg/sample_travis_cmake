cmake_minimum_required(VERSION 2.8)
# a simple test case
project (Simple)

set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_HOME_DIRECTORY}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_HOME_DIRECTORY}/bin)

add_subdirectory (Source)
add_subdirectory (simpleLib)
