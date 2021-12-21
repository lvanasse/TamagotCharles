cmake_minimum_required(VERSION 3.13.1)
set(BOARD nucleo_f401re)
set(CONF_FILE "prj.conf")

find_package(Zephyr)

project(TamagotCharles)

target_sources(app PRIVATE src/main.c)