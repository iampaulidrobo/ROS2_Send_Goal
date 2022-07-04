# ROS2_Send_Goal

 
The repo aims to give target goal to the turtlebot3 robot through a script command.
The world and respective map can be added for customise goal sending .
To test the package:
**Don't forget to source the workspace{source ~/{worspace_name}/install/setup.bash}** 



In terminal-1:
```bash
  ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py 

```
In terminal-2:

```bash
  ros2 launch turtlebot3_navigation2 navigation2.launch.py 

```
The default goal location are {0,0} and can be altered in the send_goal package node.

In terminal-3:

```bash
  ros2 run send_goal GoalCoordinate 

![Screenshot from 2022-07-04 21-17-25](https://user-images.githubusercontent.com/22745024/177188221-4a7804b5-50fb-4ec0-9bee-2f06bd36234a.png)
