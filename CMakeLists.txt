cmake_minimum_required(VERSION 3.0)

project(plasma-htmlwallpaper)

find_package(ECM 1.4.0 REQUIRED NO_MODULE)
set(CMAKE_MODULE_PATH ${ECM_MODULE_PATH})

find_package(KF5Plasma REQUIRED)

plasma_install_package(package de.unkn0wn.htmlwallpaper wallpapers wallpaper)
