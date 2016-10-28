cmake_minimum_required(VERSION 3.6)
project(pic_flame)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    .gitattributes
    .gitignore)

add_executable(pic_flame ${SOURCE_FILES})