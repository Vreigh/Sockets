cmake_minimum_required(VERSION 3.7)
project(Sockets)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp ClientUDP.cpp ClientUDP.h)
add_executable(Sockets ${SOURCE_FILES})