cmake_minimum_required(VERSION 3.15)
project(ProyectoIntegradorPEL)

set(CMAKE_CXX_STANDARD 14)

add_executable(ProyectoIntegradorPEL main.cpp Recta.h Plano.h Recta.cpp Plano.cpp Solver.cpp Solver.h)