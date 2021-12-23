cmake_minimum_required(VERSION 3.19)
project(PA3)

set(CMAKE_CXX_STANDARD 11)

add_executable(PA3 prog3.cpp lex.cpp parserInt.cpp val.cpp lex.h parserInt.h val.h)