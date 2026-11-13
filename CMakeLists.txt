cmake_minimum_required(VERSION 3.25)
project(abocpp LANGUAGES CXX)

add_executable(aboCpp "./src/main.cpp")
target_compile_features(aboCpp PUBLIC cxx_std_20)
set_target_properties(aboCpp PROPERTIES CXX_EXTENSIONS OFF)
