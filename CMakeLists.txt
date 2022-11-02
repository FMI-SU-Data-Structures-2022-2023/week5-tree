cmake_minimum_required(VERSION 3.13)

project("Week 6: Binary Tree")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Tree main.cpp Tree.h)
add_executable(Test test.cpp Tree.h)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
 