#========================================
# Tecnologias I&H
# Version 1.0
#========================================
cmake_minimum_required(VERSION 2.8)
project( Tracking )
find_package( OpenCV REQUIRED )
add_executable( Tracking demo_Tracking.cpp )
target_link_libraries( Tracking ${OpenCV_LIBS} )
