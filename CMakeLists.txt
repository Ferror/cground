cmake_minimum_required(VERSION 3.5)

project(CGround)

# Gather all sources except the main entry point
file(GLOB_RECURSE INC_FILES
    include/*.h
)
file(GLOB_RECURSE SRC_FILES
    src/*.cpp
)

set(SOURCE_FILES ${INC_FILES} ${SRC_FILES})

add_executable(LAB ${SOURCE_FILES})
