cmake_minimum_required(VERSION 3.0.2)
project(aspida_robot)


find_package(catkin REQUIRED
  roscpp
  rospy
  std_msgs
  )

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES aspida_robot
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

###########
## Build ##
###########

## Specify additional locations of header files
## Your package locations should be listed before other locations
include_directories(
# include
${catkin_INCLUDE_DIRS}
)
