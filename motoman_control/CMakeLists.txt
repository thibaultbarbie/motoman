cmake_minimum_required(VERSION 2.8.3)
project(motoman_control)
find_package(catkin REQUIRED COMPONENTS
  roscpp
  actionlib
  actionlib_msgs
  trajectory_msgs
  control_msgs
  sensor_msgs
  )

catkin_package(
  CATKIN_DEPENDS actionlib_msgs
  )



include_directories(
  ${catkin_INCLUDE_DIRS}
)
