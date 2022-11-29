project(UEmuLinuxX86)

add_executable(UEmuLinuxX86
    UEmuLinuxX86.cpp
)

target_link_libraries(UEmuLinuxX86 PUBLIC LibUEmu)