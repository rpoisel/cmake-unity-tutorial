add_library(module_a STATIC
    module_a.c
)

target_include_directories(module_a PUBLIC
    ${CMAKE_CURRENT_LIST_DIR}
)
