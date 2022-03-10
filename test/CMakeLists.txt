set(BIN test)
set(SRC test.cpp)

add_executable(${BIN} ${SRC})
target_link_libraries(${BIN} ${CONAN_LIBS})

