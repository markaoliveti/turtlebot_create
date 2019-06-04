turtlebot_create
======

It keeps iRobot Create specific packages. Here are the commands to run the turtlebot
```
cd ~/catkin_ws/src/
git clone https://github.com/markaoliveti/turtlebot_create/
cd ~/catkin_ws/
catkin_make
source devel/setup.bash
```
we need to enable usb
```
sudo usermod -a -G dialout $USER
```
Now, we can run the command
```
rosrun create_node turtlebot_node.py 
```
