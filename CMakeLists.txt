cmake_minimum_required(VERSION 3.24)
project(untitled2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_library(untitled2 library.cpp arraySum.cpp test.cpp)
