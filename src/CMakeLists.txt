cmake_minimum_required(VERSION 3.16.3)

# name of the project
project(resttest)

# set c++ standard to c++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

include_directories(/usr/local/include/)

# compile
add_executable(${PROJECT_NAME} main.cpp)

