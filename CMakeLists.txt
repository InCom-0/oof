cmake_minimum_required(VERSION 3.30)

project(OOF)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_SCAN_FOR_MODULES OFF)


add_library(OOF INTERFACE)
add_library(OOF::OOF ALIAS OOF)

target_include_directories(OOF INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/)