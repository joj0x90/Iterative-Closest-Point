# Earlier versions are not tested or supported
cmake_minimum_required(VERSION 3.18 FATAL_ERROR)

set(CMAKE_CXX_STANDARD 17)

project(
  bc_icp
  LANGUAGES CXX)

add_executable(icp "src/main.cpp" "src/ICP.cpp" "src/KdTree.cpp" "src/svd.cpp")
target_include_directories(icp PRIVATE "src/")