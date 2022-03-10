set(BIN graph-gui)
set(SRC main.cpp)

add_executable(${BIN} ${SRC})
target_link_libraries(${BIN} ${CONAN_LIBS})

