cmake_minimum_required(VERSION 3.26.3)
project(example)

add_subdirectory(pybind11)
pybind11_add_module(example example.cpp)