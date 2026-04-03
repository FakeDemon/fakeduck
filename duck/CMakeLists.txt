add_library(duck INTERFACE)

target_include_directories(duck
    INTERFACE
        ${CMAKE_CURRENT_SOURCE_DIR}
        ${CMAKE_CURRENT_SOURCE_DIR}/..
)

target_compile_features(duck INTERFACE cxx_std_20)