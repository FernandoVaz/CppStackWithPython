cmake_minimum_required(VERSION "3.19.2")

project("CppServerPlatform")
add_executable("CppServerPlatform" "src/main.cpp")

add_test("CppServerTest" "test/test_main.cpp")
add_subdirectory(test)
