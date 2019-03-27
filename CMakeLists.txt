# Define the minimum required cmake version
cmake_minimum_required(VERSION 3.5.1)
project(cpp_practice C CXX)
set(CMAKE_CXX_STANDARD 11)

# Define the version number of the project
set(cpp_practice_VERSION_MAJOR 1)
set(cpp_practice_VERSION_MINOR 0)

# Set the source directory of each of the exercises files
add_executable(helloworld ${CMAKE_CURRENT_SOURCE_DIR}/src/helloworld.cpp)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_CURRENT_SOURCE_DIR}/bin)
