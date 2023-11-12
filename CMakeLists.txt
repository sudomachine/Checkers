cmake_minimum_required(VERSION 3.14)

project(Checkers)
set(project_dir ${CMAKE_SOURCE_DIR})

set(core_dir ${project_dir}/Core)
#set(core_source)

add_executable(${PROJECT_NAME} ${project_dir}/main.cpp)
