cmake_minimum_required(VERSION 3.13)
project(cmake_testapp)

set(CMAKE_CXX_STANDARD 14)
add_executable(cmake_testapp ${PROJECT_SOURCE_DIR}/1.\ Simple\ Numbers/C/SimpleNumbers_1.c)
add_executable(cmake_testapp2 ${PROJECT_SOURCE_DIR}/1.\ Simple\ Numbers/C/SimpleNumbers_2.c)