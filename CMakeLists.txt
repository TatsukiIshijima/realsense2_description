cmake_minimum_required(VERSION 3.5)
project(realsense2_description)

find_package(ament_cmake REQUIRED)
#find_package(xacro REQUIRED)

# RealSense description

# Install files
install(
  DIRECTORY launch meshes rviz urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
