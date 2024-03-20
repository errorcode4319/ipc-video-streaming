set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_COMPILIER "/usr/bin/g++")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2 -pthread -Wno-write-strings")

include_directories(
    ${3RDPARTY_DIR}/cpp-ipc_v1.3.0/include     
)

add_subdirectory(server)