cmake_minimum_required(VERSION 3.28.3)


project(linux-internals VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_GENERATOR make)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake")

if(CMAKE_VERSION VERSION_LESS "3.7.0")
    set(CMAKE_INCLUDE_CURRENT_DIR ON)
endif()

add_subdirectory(memory-management)
add_subdirectory(multithread)
add_subdirectory(networking)
add_subdirectory(process-management)
add_subdirectory(interprocess-communication)
add_subdirectory(filesystem)
