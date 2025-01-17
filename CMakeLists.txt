cmake_minimum_required(VERSION 3.31)

project(CPPMain)

add_subdirectory(main)

set_target_properties(CPPMain PROPERTIES
    CXX_STANDARD 23
    CXX_STANDARD_REQUIRED ON
    CXX_EXTENSIONS ON
)