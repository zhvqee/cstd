cmake_minimum_required(VERSION 3.17)
project(cstd C)

set(CMAKE_C_STANDARD 11)

add_library(cstd SHARED dylib.c dylib.h)