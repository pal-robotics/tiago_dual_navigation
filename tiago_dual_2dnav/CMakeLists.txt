cmake_minimum_required(VERSION 2.8.3)
project(tiago_dual_2dnav)

find_package(catkin REQUIRED)

catkin_package()

install(
    PROGRAMS
        scripts/navigation_camera_mgr.py
    DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

foreach(dir launch config)
    install(DIRECTORY ${dir}/
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/${dir})
endforeach(dir)
