project(hello_world)
cmake_minimum_required(VERSION 3.18.0)
include(../examples.cmake)

add_example(
  hello_world
  hello_world.c
)
