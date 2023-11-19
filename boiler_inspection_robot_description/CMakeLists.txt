cmake_minimum_required(VERSION 3.0.2)
project(boiler_inspection_robot_description)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  # gazebo_ros
  joint_state_publisher
  #robot_state_publisher
  rospy
  # rviz
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES boiler_inspection_robot_description
#  CATKIN_DEPENDS controller_manager gazebo_ros joint_state_publisher robot_state_publisher rospy rviz
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
