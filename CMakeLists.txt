cmake_minimum_required(VERSION 3.10)
project(bctProject C)
set(CMAKE_C_STANDART 11)

add_executable(bst src/bst.c src/stack.c src/iterator.c src/main.c)
