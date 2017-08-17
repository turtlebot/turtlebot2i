# Software Instructions

The full software guide for the TurtleBot 2i is availble at <https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions>

It consists of:

* [Installing ROS Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)
* [Installing VNC](https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions#vncremote-ssh-setup)
* [Installing core TurtleBot packages](https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions#turtlebot-2i-ros-package-install)
* [Installing TurtleBot 2i packages](https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions#setup-turtlebot2i-source-code--catkin-environment)
* [Configuring your environment](https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions#bashrc-setup)
* [Preparing and installing udev rules](https://github.com/Interbotix/turtlebot2i/wiki/Full-Build-Instructions#udev-rules)

## Known Issues

The Intel RealSense functionality depends on [librealsense](https://github.com/IntelRealSense/librealsense) which is still in active development. Linux system updates such as kernel updates have been known to break librealsense thus preventing the sensor from starting. In the event such circunstances arise temporary work arounds may be implemented to restore functionality until fixes are available. 