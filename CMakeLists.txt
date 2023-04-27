cmake_minimum_required(VERSION 3.25)
project(MephEngine CUDA)

set(CMAKE_CUDA_STANDARD 23)

add_executable(MephEngine main.cu)

set_target_properties(MephEngine PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
