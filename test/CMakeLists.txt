## testcases for c-vector
add_executable(c-vector-example c-vector-example.c)

target_link_libraries(c-vector-example PUBLIC c-vector)

set_target_properties(c-vector-example PROPERTIES C_STANDARD 99)
target_compile_options(c-vector-example PUBLIC -Wall -Wextra)


## testcases for vector
add_executable(vector-test vector-test.c)
add_executable(vector-example vector-example.c)

target_link_libraries(vector-test vector)
target_link_libraries(vector-example vector)

