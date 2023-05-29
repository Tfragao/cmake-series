cmake_minimum_required(VERSION 3.26.3)

set(CMAKE_CXX_COMPILER "/usr/bin/clang")
project(cmake_tutorial
        VERSION 0.1
        DESCRIPTION "Learning cmake"
        LANGUAGES CXX)
add_executable(cmake_tutorial main.cpp)
target_compile_features(cmake_tutorial PRIVATE cxx_std_20)
