cmake_minimum_required(VERSION 3.1 FATAL_ERROR)
project(BRDFGenerator VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(BRDFGenerator BRDFGenerator/BRDFGenerator.cpp)
target_include_directories(BRDFGenerator PRIVATE ext/glm-0.9.8.1/glm ext/gli-0.8.2.0/gli)
