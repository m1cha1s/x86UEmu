add_subdirectory(core)
add_subdirectory(isa)
add_subdirectory(platform)

project(LibUEmu)

add_library(LibUEmu INTERFACE)

target_link_libraries(LibUEmu INTERFACE
    LibUEmuCore
    LibUEmuISA
    LibUEmuPlatform
)