cmake_minimum_required(VERSION 3.0.2)
project(boiler_inspection_robot_simulation)

find_package(catkin REQUIRED COMPONENTS
  std_msgs
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES boiler_inspection_robot_simulation
#  CATKIN_DEPENDS rospy std_msgs
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
