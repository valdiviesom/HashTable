cmake_minimum_required(VERSION 3.3)
project(221l7)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    driver.cc
    Hashtable.cc
    Hashtable.h
    Makefile)

add_executable(221l7 ${SOURCE_FILES})