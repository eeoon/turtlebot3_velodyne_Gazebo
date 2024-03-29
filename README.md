# Turtlebot3_World (burger with velodyne) Simulations for Training Gazebo.


```
mkdir -p eon_ws/src
cd ~/eon_ws/src
git clone https://github.com/eeoon/turtlebot3_velodyne_Gazebo.git
cd ~/eon_ws
colcon build
source install/setup.bash
ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py
```

