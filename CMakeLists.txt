add_library(httpcl STATIC 
	httpcl.c
)

target_include_directories(httpcl PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")
