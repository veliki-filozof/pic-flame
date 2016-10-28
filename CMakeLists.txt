cmake_minimum_required(VERSION 3.6)
project(pic_flame)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    .gitattributes
    .gitignore src/main.cpp src/main.h src/config.cpp src/config.h src/util.cpp src/util.h src/vec.h src/field.h)

add_executable(pic_flame ${SOURCE_FILES})