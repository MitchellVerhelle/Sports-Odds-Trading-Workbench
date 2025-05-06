cmake_minimum_required(VERSION 3.17)
project(Sports-Odds-Trading-Workbench LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_C_COMPILER "/opt/homebrew/Cellar/llvm/20.1.2/bin/clang")
set(CMAKE_CXX_COMPILER "/opt/homebrew/Cellar/llvm/20.1.2/bin/clang++")

add_executable(test test.cpp)

# rm -rf build
# Cmd + Shift + P to open command palette and compile
# Cmd + Shift + P to open command palette and build with Ninja (Note: Cmd + Shift + B doesn't use Ninja)
# ./build/test