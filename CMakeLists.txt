cmake_minimum_required(VERSION 3.19)

project(
    "Game"
    VERSION 1.0
    LANGUAGES CXX
)

set(GLFW_BUILD_DOCS OFF CACHE BOOL "" FORCE)
set(GLFW_BUILD_TESTS OFF CACHE BOOL "" FORCE)
set(GLFW_BUILD_EXAMPLES OFF CACHE BOOL "" FORCE)

add_subdirectory(extern/glfw)
add_subdirectory(extern/glad)

add_executable(Game src/main.cpp)

target_link_libraries(Game PRIVATE glfw PRIVATE glad)