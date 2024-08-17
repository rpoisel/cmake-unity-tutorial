add_executable(suite_1_app
    suite_1.c
)

target_link_libraries(suite_1_app
    module_a
    unity
)

add_test(suite_1_test suite_1_app)
