cmake_minimum_required(VERSION 3.10...3.29)
project(glad LANGUAGES C VERSION 1.0.0)

add_library(glad src/glad.c include/glad/glad.h include/KHR/khrplatform.h)

target_include_directories(glad PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/include")
target_include_directories(glad PRIVATE src/)