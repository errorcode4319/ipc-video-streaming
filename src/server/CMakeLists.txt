project(server)

file(GLOB sources ./*.cpp)
file(GLOB headers ./*.hpp)

add_executable(${PROJECT_NAME} ${sources} ${headers})

target_link_libraries(${PROJECT_NAME} ipc)