cmake_minimum_required(VERSION 3.15)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(formatter_ex_lib)

add_library(formatter_ex STATIC formatter_ex.cpp)
target_include_directories(formatter_ex PUBLIC )
target_link_libraries(formatter_ex PUBLIC formatter)
