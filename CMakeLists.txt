cmake_minimum_required(VERSION 3.15)
project(project_template CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON CACHE INTERNAL "") # works (in creating the compile_commands.json file)


add_subdirectory(src)



install(TARGETS ${PROJECT_NAME})
