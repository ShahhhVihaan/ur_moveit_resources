cmake_minimum_required(VERSION 3.10.2)
project(moveit_resources_ur_moveit_config)
find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY config launch rviz srdf DESTINATION share/${PROJECT_NAME})
