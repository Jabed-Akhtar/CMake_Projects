add_library(
    say-hello SHARED
    src/hello/hello.hpp
    src/hello/hello.cpp
)

target_include_directories(say-hello PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/src")