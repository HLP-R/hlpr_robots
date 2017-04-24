cmake_minimum_required(VERSION 2.8.3)
project(poli_bringup)

find_package(catkin REQUIRED COMPONENTS
  bwi_msgs
  multi_level_map_msgs
  multi_level_map_server
  multi_level_map_utils
  roscpp
  rospy
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
