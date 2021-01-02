cmake_minimum_required(VERSION 3.19)

project(HelloWorld
    LANGUAGES CXX
    VERSION 0.1.0
)

add_executable(HelloWorld src/main.cpp)
target_compile_features(HelloWorld PRIVATE cxx_std_20)