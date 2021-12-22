cmake_minimum_required(VERSION 3.22.1)
project(Lab2)

add_library(calculator STATIC calculator.cpp)
add_executable(Lab2 main.cpp)

target_link_libraries(main calculator)