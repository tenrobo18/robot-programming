robot-programming [![Build Status](https://travis-ci.org/jsk-enshu/robot-programming.svg?branch=master)](https://travis-ci.org/jsk-enshu/robot-programming) [![Join the chat at https://gitter.im/jsk-enshu/robot-programming](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jsk-enshu/robot-programming?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
=================

This is exercise for robot-programming.

```
$ source /opt/ros/melodic/setup.bash
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/src
$ git clone https://github.com/jsk-enshu/robot-programming
$ wstool init .
$ wstool merge robot-programming/.rosinstall.${ROS_DISTRO}
$ wstool update
$ rosdep update
$ rosdep install --from-paths src --ignore-src -y -r
$ cd ..
$ catkin build
$ echo 'source ~/catkin_ws/devel/setup.bash' >> ~/.bashrc ## bashrcについか
```

Documentations
=================
See online [manual](http://jsk-enshu.github.io/robot-programming/) for Euslisp models and interfaces.

PDF files are also available from [here](http://jsk-enshu.github.io/robot-programming/robot_programming_manual.pdf)

