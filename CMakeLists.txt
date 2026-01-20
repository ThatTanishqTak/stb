add_library(stb INTERFACE)
add_library(stb::stb ALIAS stb)

target_include_directories(stb SYSTEM INTERFACE
    ${CMAKE_CURRENT_LIST_DIR}
)
