cmake_minimum_required(VERSION 3.25.1)
project(main)
add_executable(myprogram main.c)
add_library(mylib SHARED lib.c)

target_link_libraries(myprogram mylib)
