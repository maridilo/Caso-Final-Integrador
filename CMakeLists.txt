cmake_minimum_required(VERSION 3.26)
project(Caso_Final_Integrador)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Caso_Final_Integrador
        tiny-lisp.cpp
        json11.hpp
        jsonlib.hpp)
