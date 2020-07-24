set(TEST_SOURCES
main.cpp
FooTest.cpp
)

add_executable("${app}_test" ${TEST_SOURCES})
add_test(NAME "${app}_test" COMMAND "${app}_test")
target_link_libraries("${app}_test" PUBLIC ${app}_lib gtest)