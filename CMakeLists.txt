cmake_minimum_required(VERSION 3.16)	
				
project(NEW)			

add_library(
	hello 
	STATIC 
	hello.cpp
)	

add_executable(
	main 
	main.cpp
)

target_link_libraries(main hello)
