cmake_minimum_required(VERSION 3.15)
project(veque)

add_library(veque INTERFACE)

target_include_directories(
    veque INTERFACE
    "${CMAKE_CURRENT_SOURCE_DIR}/include"
)