cmake_minimum_required(VERSION 3.0...3.20 FATAL_ERROR) # this req is copied from glfw's CMakeLists.txt
project(glfw_etc_1)

include_directories(glfw/include)

#add_subdirectory(glew/build/cmake)
add_subdirectory(glfw)
add_subdirectory(hello_glfw)