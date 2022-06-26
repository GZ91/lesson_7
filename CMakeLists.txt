cmake_minimum_required(VERSION 3.5)

project(lesson_7)

find_package(GTest)

add_executable(lesson_7
    main.cpp
)

set_target_properties(lesson_7 PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)

install(TARGETS lesson_7)