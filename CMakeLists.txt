cmake_minimum_required(VERSION 2.6)

add_subdirectory(core)

set(MAP2X_CORE_INCLUDE_DIR  ${CMAKE_CURRENT_SOURCE_DIR}/core/src)
set(MAP2X_CORE_LIBRARY      Map2XCore)

add_subdirectory(qt)