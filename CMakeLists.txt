cmake_minimum_required(VERSION 3.24)
project(main)

set(CMAKE_CXX_STANDARD 17)

add_executable(main main.cpp deBruijnByHash.cpp deBruijnByHash.h deBruijnByStringComp.cpp deBruijnByStringComp.h EulerPath.cpp EulerPath.h kassembler.cpp kassembler.h cmake-build-debug/kassembler.hpp sequence.cpp sequence.hpp test.cpp test.hpp)
