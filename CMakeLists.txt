cmake_minimum_required(VERSION 3.10)
project(IS_tema1)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(dependencies/c-thread)
add_subdirectory(dependencies/c-comm-stack)
include_directories(src/**)

add_executable(
        IS_tema1
        src/app/main.cpp
)