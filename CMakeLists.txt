cmake_minimum_required(VERSION 3.2)
project(vscode-demo)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -Wall -O2")


add_executable(vscode-demo vscode-demo.cpp)
