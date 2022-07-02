cmake_minimum_required(VERSION 3.20)
project(CUDABasics CUDA)

set(CMAKE_CUDA_STANDARD 17)

add_executable(CUDABasics main.cu)

set_target_properties(CUDABasics PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
