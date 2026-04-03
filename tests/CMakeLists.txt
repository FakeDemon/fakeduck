enable_testing()

add_executable(duck_test
    main.cpp
)

target_link_libraries(duck_test PRIVATE duck)
add_test(NAME duck_test COMMAND duck_test)