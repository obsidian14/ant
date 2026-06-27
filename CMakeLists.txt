cmake_minimum_required(VERSION 4.0)
project(ANT LANGUAGES C)
add_executable(ant)
set(ANT_SOURCE_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)
target_sources(
  ant
  PRIVATE
  ${ANT_SOURCE_DIR}/ant.c
)
