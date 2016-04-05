cmake_minimum_required(VERSION 3.4)
project(cbench)

option(BUILD_SHARED_LIBS "Build as a shared library." OFF)
include_directories(include)

add_subdirectory(src)

enable_testing()

add_subdirectory(tests)
