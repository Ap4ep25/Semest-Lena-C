cmake_minimum_required(VERSION 3.8)
project(untitled15)

set(CMAKE_C_STANDARD 90)

set(SOURCE_FILES main.c qdbmp.c)
add_executable(untitled15 ${SOURCE_FILES})
target_link_libraries(untitled15 m)