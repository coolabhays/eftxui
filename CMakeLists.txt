cmake_minimum_required(VERSION 3.15)
project(example_ftxui)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_subdirectory(ftxui)
add_subdirectory(src)

