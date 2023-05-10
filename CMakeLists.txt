cmake_minimum_required(VERSION 3.10)

project(
    ldpc
    LANGUAGES CXX
)

# Define the minimum C++ standard that is required
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(
    ldpc
    "Source files/example_run.cpp"
    "Source files/LDPC.cpp"
    "Source files/nrLDPCTables.cpp"
    "Source files/LDPC.h"
)
