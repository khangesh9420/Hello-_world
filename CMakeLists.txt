cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(HelloWorld VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(hello_world hello_world.cpp)

