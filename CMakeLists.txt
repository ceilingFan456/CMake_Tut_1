cmake_minimum_required(VERSION 3.10.0)

project(dummy_project VERSION 1.0)

add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/lib/c-vector)
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/lib/vector)
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/test)