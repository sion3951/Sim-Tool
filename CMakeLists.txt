cmake_minimum_required(VERSION 3.5.0)
project(Sim-Tool VERSION 0.1.0 LANGUAGES C CXX)

include_directories("${CMAKE_CURRENT_SOURCE_DIR}/libs/*.cpp")
include_directories("${CMAKE_CURRENT_SOURCE_DIR}/libs/*.h")

file(GLOB SOURCES "${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp")
add_executable(Sim-Tool ${SOURCES})
