add_library(vector SHARED vector.c)
add_library(vector-static STATIC vector.c)

target_include_directories(vector PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")

target_compile_options(vector PUBLIC -O3 -Os -std=c99 -g)