cmake_minimum_required(VERSION 3.17)
project(daemon__)

set(CMAKE_CXX_STANDARD 14)

add_executable(daemon__ main.cpp ServalCharger.cpp ServalCharger.h)