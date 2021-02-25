cmake_minimum_required(VERSION 3.17)
project(main)

set(CMAKE_CXX_STANDARD 20)

add_executable(main main.cpp main.h src/core/core.h src/core/foo.cpp)