vgc_add_library(dom
    THIRD_DEPENDENCIES

    VGC_DEPENDENCIES
        core

    HEADER_FILES
        api.h
        attribute.h
        document.h
        element.h
        exceptions.h
        io.h
        node.h
        value.h
        xmlformattingstyle.h

    CPP_FILES
        attribute.cpp
        document.cpp
        element.cpp
        exceptions.cpp
        io.cpp
        node.cpp
        value.cpp
        xmlformattingstyle.cpp

    COMPILE_DEFINITIONS
)

add_subdirectory(wraps)
add_subdirectory(tests)
