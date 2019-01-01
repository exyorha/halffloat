cmake_minimum_required(VERSION 3.12)
project(halffloat)

add_library(halffloat STATIC
	include/half.h
	half.cpp
)

target_include_directories(halffloat PUBLIC include)
