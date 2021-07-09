cmake_minimum_required(VERSION 3.14)
project(pool)

set(CMAKE_CXX_STANDARD 17)
set(SOURCE_FILES main.cpp object_pool.hpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})