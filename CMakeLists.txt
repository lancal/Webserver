cmake_minimum_required(VERSION 3.9)
project(Webserver)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(Webserver ${SOURCE_FILES})