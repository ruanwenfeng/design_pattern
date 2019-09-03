set(PROJECT_NAME "app")

set(PROJECT_SRC
	main.cpp
)
add_executable(${PROJECT_NAME} ${PROJECT_SRC} ${PROJECT_HEADERS} ) #

target_link_libraries(${PROJECT_NAME} common)