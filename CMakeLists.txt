add_library(httpcl STATIC 
    httpcl.c
)

target_include_directories(httpcl PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")

set_target_properties(httpcl PROPERTIES POSITION_INDEPENDENT_CODE ON)
