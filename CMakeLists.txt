cmake_minimum_required(VERSION 3.0)
message("Building args")
# define the project
project(args)

# create and configure the library target
add_library(${PROJECT_NAME} INTERFACE)
SET(CMAKE_CXX_STANDARD 11)
target_include_directories(${PROJECT_NAME} INTERFACE .)
