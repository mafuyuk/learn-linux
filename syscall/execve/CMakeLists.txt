cmake_minimum_required(VERSION 3.5)

set(SOURCE_FILES
        ${CMAKE_CURRENT_SOURCE_DIR}/main.c
        )
add_executable(execve ${SOURCE_FILES})