cmake_minimum_required(VERSION 3.0)
project(main LANGUAGES CXX C)

include_directories(include)
file(GLOB_RECURSE sources src/*)

add_executable(a.out main.cpp ${sources})