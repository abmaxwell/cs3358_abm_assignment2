cmake_minimum_required(VERSION 3.8)
project(cs3358_abm_assignment2)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
    Assign02.cpp
    IntSet.cpp
    IntSet.h)

add_executable(cs3358_abm_assignment2 ${SOURCE_FILES})