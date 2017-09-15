cmake_minimum_required(VERSION 3.8)
project(Assign02StarterFiles)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    Assign02.cpp
    IntSet.cpp
    IntSet.h)

add_executable(Assign02StarterFiles ${SOURCE_FILES})