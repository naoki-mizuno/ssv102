cmake_minimum_required(VERSION 2.8.3)
project(ssv102)

find_package(catkin REQUIRED)

catkin_package()

catkin_python_setup()

catkin_install_python(PROGRAMS
    nodes/ssv102_node.py
    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
