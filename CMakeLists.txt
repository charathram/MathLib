cmake_minimum_required(VERSION 3.13)

project(MathLib)

add_library(MathLib INTERFACE)

target_include_directories(MathLib INTERFACE ${CMAKE_CURRENT_LIST_DIR}/include)

target_sources(MathLib INTERFACE
        ${CMAKE_CURRENT_LIST_DIR}/mathlib.c
)
