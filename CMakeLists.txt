cmake_minimum_required(VERSION 3.10)
project(RayTracingInOneWeekend LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(src/common)

add_executable(weekend src/weekend/main.cc)

set_target_properties(weekend PROPERTIES RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/output")