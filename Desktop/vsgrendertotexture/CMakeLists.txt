set(SOURCES
    vsgrendertotexture.cpp
)

add_executable(vsgrendertotexture ${SOURCES})

target_link_libraries(vsgrendertotexture vsg)
