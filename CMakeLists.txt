cmake_minimum_required(VERSION 3.8)
project(str_d)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c my_str_t.h)
add_executable(str_d ${SOURCE_FILES})