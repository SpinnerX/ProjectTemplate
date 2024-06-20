set(
    all_src
    Application.cpp
)

set(
    all_headers
    ../project_template/Application.h
)

add_library(${PROJECT_NAME} ${all_headers} ${all_src})

target_include_directories(${PROJECT_NAME} PUBLIC "${CMAKE_SOURCE_DIR}/project_template")