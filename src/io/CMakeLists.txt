add_library(CLI-IO
        cli.cpp
        helper.cpp
)

# Add src directory to path for header includes
target_include_directories(CLI-IO PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})