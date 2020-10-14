cmake_minimum_required(VERSION 3.17)
project(IS_tema1)

set(CMAKE_CXX_STANDARD 20)

include_directories(src/*)

add_executable(
        IS_tema1
        src/app/main.cpp
)