cmake_minimum_required(VERSION 2.8.3)
project(youbot_gazebo_worlds)

find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS
)

install(DIRECTORY launch/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch)
install(DIRECTORY urdf/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/urdf)
install(DIRECTORY worlds/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/worlds)
