cmake_minimum_required(VERSION 3.21)
project(RSA)

set(CMAKE_CXX_STANDARD 14)

add_executable(rsa main.cpp headers/crypto_engine.h sources/crypto_engine.cpp)
