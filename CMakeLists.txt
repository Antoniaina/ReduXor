cmake_minimum_required(VERSION 3.10)
project(ReduXor)

set(CMAKE_CXX_STANDARD 17)

add_executable(ReduXor
    src/main.cpp
    src/core/expression.cpp
    src/core/simplifier.cpp
)
