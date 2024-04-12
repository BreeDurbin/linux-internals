
set(subproject_name "multithread")

set (CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin/${subproject_name})

set(SOURCE_FILES
    ${CMAKE_CURRENT_SOURCE_DIR}/main.cpp
)

add_executable(
    ${subproject_name}
    #sources
    ${SOURCE_FILES}
)

