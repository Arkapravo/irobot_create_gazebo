roomba_icreate_gazebo
=====================

Roomba icreate simulations in gazebo (ROS Electric)

Fork in
-------
A good part of this repository is forked in from the following, 

(1) icreate URDF is from http://code.google.com/p/aptima-ros-pkg/  
(2) erratic gazebo plugin is from https://code.google.com/p/ua-ros-pkg/       

Installation
------------
ROS Electric installation (http://ros.org/wiki/electric) is needed for these packages. It is preferred that gazebo (http://www.ros.org/wiki/simulator_gazebo?distro=electric) should be also be build and installed.

Build and install (rosmake) all three of packages; _erratic_gazebo_plugins_, _icreate_gazebo_ and _irobot_create_description_ and make sure that these are on the ROS PATH. 

It may be required to install _ros_comm_ from http://www.ros.org/wiki/ros_comm

Running the simulation
----------------------
The simulation can be started with,

  _roslaunch icreate_gazebo file_1.launch_
  
![Image Alt](http://3.bp.blogspot.com/-WERRDMHcMpM/TxMG94A0GgI/AAAAAAAAB3k/uhVxcVJ0Clw/s1600/Screenshot-2.png)

![Image Alt](http://4.bp.blogspot.com/-DrqKcNVLbKQ/TxMGX80HoFI/AAAAAAAAB3U/Ef_bT4CAHnw/s1600/Screenshot-3.png)

Testing
-------
Successfully tested on Ubuntu 10.04 LTS (ROS Electric, 1.4.10) and Ubuntu 11.10 (ROS Electric, 1.6.9)
