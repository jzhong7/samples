cmake_minimum_required(VERSION 3.4)
project(02_stackADTLinkBased)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(02_stackADTLinkBased ${SOURCE_FILES})