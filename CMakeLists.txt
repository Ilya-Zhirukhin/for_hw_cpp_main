cmake_minimum_required(VERSION 3.24)
project(hw_02)

set(CMAKE_CXX_STANDARD 14)

add_executable(main main.cpp)
add_executable(for_hw_01 hw_01.cpp)
add_executable(for_hw_02 hw_02.cpp)

find_package(Catch2 REQUIRED)
target_link_libraries(for_hw_02 Catch2::Catch2)
target_link_libraries(for_hw_01 Catch2::Catch2)

set(CMAKE_CXX_COMPILER "/usr/bin/g++")


