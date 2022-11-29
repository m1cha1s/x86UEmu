add_subdirectory(linux)

project(LibUEmuPlatform)

add_library(LibUEmuPlatform INTERFACE)

target_link_libraries(LibUEmuPlatform INTERFACE
    LibUEmuLinux
)