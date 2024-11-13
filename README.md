# Multiple Turtlebot3 in the default world

```bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/pranjalkole/multiple_turtlebot3.git
cd ..
catkin_make
roslaunch multiple_turtlebot3 multiple_turtlebot3.launch
```

For moving robot 1 use `rosrun teleop_twist_keyboard teleop_twist_keyboard.py cmd_vel:=/robot1/cmd_vel`. Similarly for robot 2, use `rosrun teleop_twist_keyboard teleop_twist_keyboard.py cmd_vel:=/robot2/cmd_vel`
