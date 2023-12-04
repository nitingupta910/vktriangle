cmake_minimum_required(VERSION 3.22)
project(vktriangle)

set(CMAKE_CXX_STANDARD 20)

find_package(Vulkan REQUIRED)

add_executable(vktriangle main.cpp
)

target_link_libraries(vktriangle
        Vulkan::Vulkan
        glfw
)

target_include_directories(vktriangle PRIVATE
)