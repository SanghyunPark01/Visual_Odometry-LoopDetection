cmake_minimum_required(VERSION 2.8)

project(VOLD)

find_package(OpenCV REQUIRED)
find_package(DBoW2 REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS} ${DBoW2_INCLUDE_DIRS})
add_executable(VOLD main.cpp)
target_link_libraries(VOLD ${OpenCV_LIBS} ${DBoW2_LIBS})
