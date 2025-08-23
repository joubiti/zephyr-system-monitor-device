
cmake_minimum_required(VERSION 3.22)
set(BOARD esp32)

find_package(Zephyr)
project(zephyr_system_monitor)
target_sources(app PRIVATE src/main.c)


