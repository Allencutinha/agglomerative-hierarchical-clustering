cmake_minimum_required(VERSION 2.8)
find_package(OpenCV REQUIRED)
project(clustering)

add_executable(cluster agglomerate.cpp)
target_link_libraries(cluster ${OpenCV_LIBS})

