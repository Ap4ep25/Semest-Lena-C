cmake_minimum_required(VERSION 3.8)
project(untitled16)

set(CMAKE_C_STANDARD 90)

set(SOURCE_FILES main.c qdbmp.c)
add_executable(untitled16 ${SOURCE_FILES})
target_link_libraries(untitled16 m)