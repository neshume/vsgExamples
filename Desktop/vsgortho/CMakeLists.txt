set(SOURCES
    vsgortho.cpp
)

add_executable(vsgortho ${SOURCES})

target_link_libraries(vsgortho vsg)
