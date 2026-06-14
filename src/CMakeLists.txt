add_subdirectory(io)

add_executable(CLI main.cpp)

target_link_libraries(CLI-IO PRIVATE RSA-IO)

target_link_libraries(CLI PRIVATE Base256 RSA-IO)
