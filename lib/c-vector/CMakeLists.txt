add_library(c-vector INTERFACE)

target_sources(c-vector INTERFACE
	${CMAKE_CURRENT_SOURCE_DIR}/cvector.h
)

target_include_directories(c-vector INTERFACE "${CMAKE_CURRENT_SOURCE_DIR}")