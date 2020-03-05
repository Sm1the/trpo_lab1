cmake_minimum_required(VERSION 3.15)
project(trpo_lab1)

set(CMAKE_CXX_STANDARD 14)

add_executable(trpo_lab1 main.cpp boardgenerate.h boardgenerate.cpp board_read.h board_read.cpp board_start.h board_start.cpp board_print_plain.h board_print_plain.cpp)