cmake_minimum_required(VERSION 2.8.3)
project(tiago_dual_laser_sensors)

find_package(catkin REQUIRED)

catkin_package()

foreach(dir launch)
    install(DIRECTORY ${dir}/
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/${dir})
endforeach(dir)
