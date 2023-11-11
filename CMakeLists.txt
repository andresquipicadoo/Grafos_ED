cmake_minimum_required(VERSION 3.26)
project(grafos_ed)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(grafos_ed
        INodo.h
        grafos/Arco.h)
