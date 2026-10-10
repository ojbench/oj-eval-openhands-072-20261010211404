cmake_minimum_required(VERSION 3.10)
project(riscv_simulator C)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR})
add_executable(code code.c)
