cmake_minimum_required(VERSION 3.5)
project(micropather)

add_library(micropather micropather.cpp micropather.h)
target_include_directories(micropather PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
