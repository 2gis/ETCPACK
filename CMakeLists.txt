cmake_minimum_required(VERSION 3.25)
project(etcpack)

set(CMAKE_CXX_STANDARD 20)

add_executable(etcpack source/image.cxx source/etcpack.cxx source/etcdec.cxx)
