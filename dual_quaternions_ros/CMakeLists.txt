cmake_minimum_required(VERSION 2.8.3)
project(dual_quaternions_ros)

find_package(catkin REQUIRED COMPONENTS
  rospy
  geometry_msgs
  dual_quaternions
)

catkin_package()

catkin_python_setup()
