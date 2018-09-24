cmake_minimum_required(VERSION 3.10)
project(clox C)

set(CMAKE_C_STANDARD 11)

add_executable(clox main.c common.h chunk.h chunk.c memory.h memory.c debug.c debug.h value.c value.h compiler.c compiler.h scanner.c scanner.h vm.c vm.h object.h object.c)