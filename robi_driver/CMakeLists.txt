cmake_minimum_required(VERSION 2.8.3)
project(robi_driver)

find_package(catkin REQUIRED COMPONENTS message_generation std_msgs)

add_message_files(FILES Servo.msg)

generate_messages(DEPENDENCIES std_msgs)

catkin_package(CATKIN_DEPENDS message_runtime)

install(DIRECTORY example launch scripts
  DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
  USE_SOURCE_PERMISSIONS)

