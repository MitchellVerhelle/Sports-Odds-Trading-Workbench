cmake_minimum_required(VERSION 3.21)
project(MyProject SportOddsTradingWorkbench)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_C_COMPILER "/opt/homebrew/Cellar/llvm/20.1.2/bin/clang")
set(CMAKE_CXX_COMPILER "/opt/homebrew/Cellar/llvm/20.1.2/bin/clang++")

add_executable(test test.cpp)