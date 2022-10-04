cmake_minimum_required(VERSION 3.17)
project(untitled2)

#set(CMAKE_CXX_STANDARD 14)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -fopenmp")
add_executable(untitled2 main.cpp)