cmake_minimum_required(VERSION 3.12)
project(testKlasy)

set(CMAKE_CXX_STANDARD 17)

add_executable(wallet wallet_example.cc wallet.cc wallet.h)