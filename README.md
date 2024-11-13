# Multiple Turtlebot3 in the default world

## Building

```bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/pranjalkole/multiple_turtlebot3.git
cd ..
catkin_make
roslaunch multiple_turtlebot3 multiple_turtlebot3.launch
```

In another terminal,
```bash
rosrun multiple_turtlebot3 keyboard.py
```
