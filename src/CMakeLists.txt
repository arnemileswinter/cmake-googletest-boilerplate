set(SOURCES
    main.cpp
    Foo.cpp
)

add_executable("${app}_run" ${SOURCES})
add_library("${app}_lib" STATIC ${SOURCES})