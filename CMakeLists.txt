
cmake_minimum_required(VERSION 2.8)
project(cmaes)

add_executable(example_short src/example_short.c src/cmaes.c src/cmaes.h)
add_executable(example_restarts src/example_restarts.c src/cmaes.c src/cmaes.h)
add_executable(example_boundary src/example_boundary.c  src/boundary_transformation.c src/cmaes.c src/boundary_transformation.h src/cmaes.h)
