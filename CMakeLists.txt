cmake_minimum_required(VERSION 3.25)
project(OPC)

set(CMAKE_CXX_STANDARD 17)

add_executable(OPC main.cpp src/test.cpp src/test.h)
