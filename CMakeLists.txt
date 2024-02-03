cmake_minimum_required(VERSION 3.28.1)
project(SoftwareDesignCpp)

set(CMAKE_CXX_STANDARD 17)

enable_testing()

option(BUILD_1.1 "Enable building Program 1.1" ON)

if(BUILD_1)
    add_subdirectory(CH_01/Program1.1-Mak-Changes)
endif()