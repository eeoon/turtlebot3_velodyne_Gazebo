# Turtlebot3_World (burger with velodyne) Simulations for Training Gazebo.

## Installation Gazebo (humble)
```
source /opt/ros/humble/setup.bash
sudo apt-get update

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
cd ..
colcon build
source install/setup.bash
export TURTLEBOT3_MODEL=burger
. /usr/share/gazebo/setup.sh
```

## Run
```
ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py
```

