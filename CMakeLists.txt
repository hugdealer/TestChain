cmake_minimum_required(VERSION 3.15)
project(TestChain)

set(CMAKE_CXX_STANDARD 14)

add_executable(TestChain main.cpp Block.cpp Block.h sha256.cpp sha256.h Blockchain.cpp Blockchain.h)