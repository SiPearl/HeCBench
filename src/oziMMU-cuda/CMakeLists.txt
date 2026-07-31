# oziMMU-cuda/CMakeLists.txt

add_hecbench_benchmark(
    NAME oziMMU
    MODEL cuda
    SOURCES main.cpp
    CATEGORIES math
    LINK_LIBRARIES cublas
)
