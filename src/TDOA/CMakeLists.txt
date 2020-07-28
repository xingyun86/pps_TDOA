
set(project_name tdoa)
project(${project_name})

file(GLOB SOURCES "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")

add_executable(${project_name} ${SOURCES})
