cmake_minimum_required(VERSION 3.14)
project(ZenS)

set(CMAKE_CXX_STANDARD 14)

include_directories("Bracelet Main")

add_executable(ZenS
        "Bracelet Main/Controler.cpp"
        "Bracelet Main/Controler.h"
        "Bracelet Main/Device.cpp"
        "Bracelet Main/Device.h"
        "Bracelet Main/Gest_Data.cpp"
        "Bracelet Main/Gest_Data.h"
        "Bracelet Main/Gest_Quantity_Data.cpp"
        "Bracelet Main/Gest_Quantity_Data.h"
        "Bracelet Main/Gesture.cpp"
        "Bracelet Main/Gesture.h"
        "Bracelet Main/Order.cpp"
        "Bracelet Main/Order.h"
        "Bracelet Main/Setting.h")
