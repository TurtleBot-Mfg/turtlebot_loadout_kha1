cmake_minimum_required(VERSION 2.8.3)
project(turtlebot_loadout_kha1)

find_package(catkin REQUIRED)

catkin_package()

include_directories()

catkin_add_env_hooks(70.turtlebot_loadout_kha1 SHELLS sh DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/env-hooks)
