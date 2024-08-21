
## robocon testbot simulations

### How to setup ?

clone this repo in your workspace

```
git clone https://github.com/VIIT-Robotics-Club/testbot_sim
```

build your workspace
```
colcon build --symlink-install
```

source your ros2 workspace and launch the following file
```
ros2 launch testbot_sim turtlebot3_robocon.launch.py 
```
