cmake_minimum_required(VERSION 3.20)
project(GJParametric)

set(CMAKE_CXX_STANDARD 17)

# Third-party
find_package(OpenCASCADE REQUIRED)

add_subdirectory(src)

