cmake_minimum_required(VERSION 4.0)
project(LCD_i2c_GSOE)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(LCD_i2c_GSOE
        LCD.cpp
        LCD.h
        SoftwareI2C.cpp
        SoftwareI2C.h)
