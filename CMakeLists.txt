cmake_minimum_required(VERSION 3.21)
project(untitled4 C)

set(CMAKE_C_STANDARD 99)
include_directories(${CMAKE_SOURCE_DIR})
add_executable(untitled4 main.c miniz.c)
