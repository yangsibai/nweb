cmake_minimum_required(VERSION 2.8.4)
project(nweb)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    client.c
    nweb23.c)

add_executable(nweb ${SOURCE_FILES})