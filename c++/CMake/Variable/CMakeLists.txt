cmake_minimum_required(VERSION 2.6)

PROJECT(VARIABLEDEMO)
set(CMAKE_BUILD_TYPE DEBUG)

#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTESTFLAG")

ADD_EXECUTABLE(VARIABLEDEMO Variable.cpp)
