cmake_minimum_required(VERSION 3.0.2)
project(picar)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
  std_msgs
  picar_msgs
)


catkin_package()
catkin_python_setup()


include_directories(${catkin_INCLUDE_DIRS})


