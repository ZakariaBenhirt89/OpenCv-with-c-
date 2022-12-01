cmake_minimum_required(VERSION 3.23)
project(untitled4)

set(CMAKE_CXX_STANDARD 14)
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable(untitled4 main.cpp)
target_link_libraries( untitled4 ${OpenCV_LIBS} )

