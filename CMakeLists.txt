cmake_minimum_required(VERSION 3.21)
project(llp_lab2 C)

set(CMAKE_C_STANDARD 99)

add_executable(LLP2 main.c include/ast.h ast.c show_tree.c include/show_tree.h)
