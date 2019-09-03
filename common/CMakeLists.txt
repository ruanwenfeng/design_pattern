set(PROJECT_NAME "common")
aux_source_directory(. PROJECT_SRC)
# set(PROJECT_SRC
#	
# )
add_library(${PROJECT_NAME} ${PROJECT_SRC} ${PROJECT_HEADERS} ) #
# target_link_libraries(${PROJECT_NAME} )