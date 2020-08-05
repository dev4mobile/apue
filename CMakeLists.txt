cmake_minimum_required(VERSION 3.17)
project(apue C)

set(CMAKE_C_STANDARD 99)

add_executable(apue main.c include/apue.h)