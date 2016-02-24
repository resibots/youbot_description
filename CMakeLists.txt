cmake_minimum_required(VERSION 2.8.3)
project(youbot_description)

find_package(catkin REQUIRED)

catkin_package(
  CATKIN_DEPENDS
)

install(DIRECTORY controller/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/controller)
install(DIRECTORY meshes/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/meshes)
install(DIRECTORY robots/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/robots)
install(DIRECTORY urdf/ DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/urdf)
