cmake_minimum_required(VERSION 2.6.0)
project(convert_poses)

add_executable(convert_poses main.cpp ${SOURCE_FILES})
target_link_libraries(convert_poses ${LIBRARIES})
