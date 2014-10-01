cmake_minimum_required(VERSION 2.8.3)

project(turtlebot_hector_mapping)

find_package(catkin REQUIRED COMPONENTS
  hector_sensors_description
  turtlebot_description
  turtlebot_gazebo
  hector_sensors_description
  hector_mapping
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
