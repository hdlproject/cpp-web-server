cmake_minimum_required(VERSION 3.19)
project(cpp_web_server VERSION 1.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(include)
file(GLOB SOURCES "src/*.cpp")

add_executable(cpp_web_server ${SOURCES})