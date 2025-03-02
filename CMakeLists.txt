cmake_minimum_required(VERSION 3.10)

# Project Name
project(RayTracer)

# Specify C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add source files
set(SOURCES
    src/main.cpp
)

add_executable(RayTracer ${SOURCES})
include_directories(include)