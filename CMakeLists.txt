cmake_minimum_required(VERSION 2.8.8)
project(DesignPattern)
include_directories(
	${CMAKE_CURRENT_BINARY_DIR}
	${CMAKE_CURRENT_SOURCE_DIR}
)
message("CMAKE_CURRENT_SOURCE_DIR=${CMAKE_CURRENT_SOURCE_DIR}")
add_subdirectory("app")
add_subdirectory("common")