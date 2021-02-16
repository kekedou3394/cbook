cmake_minimum_required(VERSION 3.17)
project(cbooks C)

set(CMAKE_C_STANDARD 99)

add_executable(cbooks main.c ch01/hello_world.h ch01/hello_world.c)