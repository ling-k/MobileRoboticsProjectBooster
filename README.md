# MobileRoboticsProjectBooster
Homework for project booster
# Part 1 

- install gazebo_ros_pkgs 
    
    - instruction: `http://gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros` 

`git clone https://github.com/ros-simulation/gazebo_ros_pkgs.git -b melodic-devel` 

dependency:

    in the src folder:
        gazebo_ros_pkgs
        turtlebot3
        turtlebot3_msgs
        apriltags_ros
    
    in Home folder:
        apriltag_gazebo_model_generator (need to generate tags in gazebo home folder, check booster description in Canvas)

├── CMakeLists.txt
├── include
│   └── booster1
├── launch
│   ├── april.launch
│   └── start.launch
├── package.xml
├── src
└── worlds
    └── cafe.world
