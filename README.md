# gazebo_ros_pkgs
----
Nicolas Escobar 2023-11-09
Deleted all packages except `gazebo_plugins` so they continue to build from ROS source.

Nicolas Escobar 2023-07-11
`gazebo_plugins/src/gazebo_ros_diff_drive.cpp` Line 354
Change default `cmd_vel_sub` from "cmd_vel" to "diff_cont/cmd_vel_unstamped"
Allows for controller switching compatability, overcomes <command_topic> parameter not working
----

[![Build Status](http://build.ros.org/buildStatus/icon?job=Kpr__gazebo_ros_pkgs__ubuntu_xenial_amd64)](http://build.ros.org/job/Kpr__gazebo_ros_pkgs__ubuntu_xenial_amd64)

Wrappers, tools and additional API's for using ROS with the Gazebo simulator. Formally simulator_gazebo stack, gazebo_pkgs is a meta package. Now Catkinized and works with the standalone Gazebo debian.

### Installation
[Installing gazebo_ros_pkgs](http://gazebosim.org/tutorials?tut=ros2_installing&cat=connect_ros)

### Documentation and Tutorials
[On gazebosim.org](http://gazebosim.org/tutorials?cat=connect_ros)

### Develop and Contribute

See [Contribute](https://github.com/ros-simulation/gazebo_ros_pkgs/blob/ros2/CONTRIBUTING.md) page.


