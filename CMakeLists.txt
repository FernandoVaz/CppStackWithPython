cmake_minimum_required(VERSION "3.19.2")
project(CppServerPlatform)

# GoogleTest requires at least C++14
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(CppServerPlatform src/main.cpp)
add_subdirectory(test)
