cmake_minimum_required(VERSION 3.12)
project(VCSCheckoutTestIdeaFilesCMakeLists)

set(CMAKE_CXX_STANDARD 14)

add_subdirectory(sub_dir)

add_executable(VCSCheckoutTestIdeaFilesCMakeLists main.cpp source/source.cpp source/source.h)