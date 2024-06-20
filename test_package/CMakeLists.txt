cmake_minimum_required(VERSION 3.15)
project(PackageTest CXX)

find_package(project_template CONFIG REQUIRED)



add_executable(example src/example.cpp)
target_link_libraries(example project_template::project_template)
