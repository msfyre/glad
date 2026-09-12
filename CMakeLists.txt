cmake_minimum_required(VERSION 3.16)

project(concilia_glad
	LANGUAGES
		C
)

add_library(concilia_glad
	./src/glad.c
)

target_include_directories(concilia_glad
	PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include/
)
