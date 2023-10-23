cmake_minimum_required (VERSION 3.8)

project (INI_parser)

include_directories(Exception)

add_executable (INI_parser INI_parser.cpp INI_parser.h Exception/Exception.cpp Exception/Exception.h)

#add_subdirectory(Exception)
