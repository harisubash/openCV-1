cmake_minimum_required(VERSION 2.8)
project( DisplayImage )
find_package( OpenCV REQUIRED )
add_executable( first first.cpp )
target_link_libraries( first ${OpenCV_LIBS} )

