cmake_minimum_required(VERSION 3.27.8)
project(SoftwareDesignCpp)

set(CMAKE_CXX_STANDARD 17)

enable_testing()

#option(BUILD_1_1 "Enable building Program 1.1" ON)
#option(BUILD_1_2 "Enable building Program 1.2" ON)

#if(BUILD_1_1)
#
#endif()
#if(BUILD_1_2)
#
#endif()

add_subdirectory(CH_01/Program1.1-Mak-Changes)
add_subdirectory(CH_01/Program1.2-Mak-Complexity)
add_subdirectory(CH_01/Program1.3-Mak-Inflexible)
add_subdirectory(CH_01/Program1.4-Mak-Surprise)

add_subdirectory(CH_02/Program2.1-Mak-Books-1)
add_subdirectory(CH_02/Program2.2-Mak-Books-2)
add_subdirectory(CH_02/Program2.3-Mak-Books-3)

