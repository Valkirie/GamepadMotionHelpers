cmake_minimum_required(VERSION 3.8)

set(project "GamepadMotion")

set(all_file
  "GamepadMotion.cpp"
 )

 set(BUILD_SHARED_LIBS true)
 set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS true)

add_library(${project} ${all_file})

