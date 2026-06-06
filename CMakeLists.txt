cmake_minimum_required(VERSION 3.10.0)
project(Untitled-1.c VERSION 0.1.0 LANGUAGES C)

add_executable(Untitled-1.c Untitled-1.c)

include(CTest)
enable_testing()

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
