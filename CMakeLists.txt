cmake_minimum_required(VERSION 3.13)
project(Asg5_EyasRashid)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Asg5_EyasRashid
        dlist.cpp.h
        dlist.h
        driver.cpp
        slist.cpp.h
        slist.h)
