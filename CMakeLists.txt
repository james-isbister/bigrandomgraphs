cmake_minimum_required(VERSION 3.10)
project(pybrg)
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/pybind11)
pybind11_add_module(pybrg ./src/wrapper_bindings.cpp)
