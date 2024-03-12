## opencv-mobile
This project is for rv1103 platform.

## usage
set(OpenCV_DIR "${CMAKE_CURRENT_SOURCE_DIR}/lib/cmake/opencv4")
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

mkdir build; cd build; cmake ..; make

## license
MIT by Jim
