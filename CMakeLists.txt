cmake_minimum_required(VERSION 3.18)

project(hw VERSION 1.0.0)

add_executable(hw hw.c)

include(CPack)
add_custom_target(dist make package)
