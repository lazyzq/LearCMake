cmake_minimum_required(VERSION 3.5)
project(HelloApp
LANGUAGES CXX)
add_executable(HelloAppBinary main.cpp)
target_compile_features(HelloAppBinary PRIVATE cxx_std_20)