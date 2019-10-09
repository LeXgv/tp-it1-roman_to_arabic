cmake_minimum_required(VERSION 3.12.4)
project(clion C)

message(${CMAKE_BINARY_DIR})
set(CMAKE_C_STANDARD 99)

add_executable(clion main.c)

INSTALL(TARGETS clion DESTINATION  ${CMAKE_BINARY_DIR}/../bin)

