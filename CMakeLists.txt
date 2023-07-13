add_library(
  bc_icp STATIC "src/main.cpp" "src/ICP.cpp" "src/KdTree.cpp" "src/svd.cpp")

target_include_directories(bc_icp PUBLIC "include/")