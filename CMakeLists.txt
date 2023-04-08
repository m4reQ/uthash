cmake_minimum_required(VERSION 3.22)

project(uthash)

add_library(uthash INTERFACE)
target_include_directories(uthash INTERFACE "src")
