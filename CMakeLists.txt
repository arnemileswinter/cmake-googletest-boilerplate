cmake_minimum_required(VERSION 3.10)

set(app ProjectWithGtest)
project(${app})

include_directories(src)

add_subdirectory(src)
add_subdirectory(test)
add_subdirectory(lib/googletest)
