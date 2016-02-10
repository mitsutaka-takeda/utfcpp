cmake_minimum_required (VERSION 3.0)
project (utf8cpp)

add_library(utfcpp INTERFACE)
target_include_directories(utfcpp INTERFACE source)
  
add_subdirectory (samples)
add_subdirectory (test_drivers)
