add_subdirectory(x86)

project(LibUEmuISA)

add_library(LibUEmuISA INTERFACE)

target_link_libraries(LibUEmuISA INTERFACE
    LibUEmuX86
)