# Turtlebot3_World (burger with velodyne) Simulations for Training Gazebo.

## Installation Gazebo (humlbe)
```
source /opt/ros/humble/setup.bash
sudo apt-get update

sudo apt-get install lsb-release wget gnupg

sudo apt-get install ros-humble-ros-gz
확인중.,

sudo apt install ros-humble-gazebo-ros

sudo apt install ros-humble-gazebo-ros-pkgs

```

example,
`sudo apt-get install ros-${ROS_DISTRO}-ros-gz`

## Installation Turtlebot3_Dependency

## Installation Packages

```
source /opt/ros/humble/setup.bash
sudo apt-get update
mkdir -p eon_ws/src
cd ~/eon_ws/src
git clone https://github.com/eeoon/turtlebot3_velodyne_Gazebo.git
cd ~/eon_ws
colcon build
source install/setup.bash
export TURTLEBOT3_MODEL=burger
ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py
```

