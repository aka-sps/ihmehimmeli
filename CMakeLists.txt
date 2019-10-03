cmake_minimum_required(VERSION 3.12)

project(ihmehimmeli)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)

if(MSVC)
add_definitions(-D_USE_MATH_DEFINES)
endif(MSVC)

include_directories(.)

add_subdirectory(tempcoding)
add_subdirectory(abseil-cpp)
