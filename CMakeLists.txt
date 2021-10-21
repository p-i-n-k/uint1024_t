cmake_minimum_required(VERSION 3.20)
project(uint1024_t C)

set(CMAKE_C_STANDARD 99)

add_executable(uint1024_t main.c uint1024_t.c uint1024_t.h)
