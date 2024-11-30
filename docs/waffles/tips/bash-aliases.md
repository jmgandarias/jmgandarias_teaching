---  
title: Bash Aliases  
---

*Bash aliases* are abbreviations for long terminal commands. Some common ROS commands that we use when working with the robots are pretty long, so we've created a few aliases to make it quicker to launch certain things. Most of these are for commands that you'll run on the laptop, but there are a couple that apply to the robot too. See the table below for the full list of bash aliases that are available to you when working with the robots and the laptops:

<center>

| Alias | Full Command | Context |
| :--- | :--- | :--- |
| `tb3_teleop` | `roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch` | Laptop |
| `tb3_bringup` | `roslaunch turtlebot3_bringup turtlebot3_remote.launch` | Laptop |
| `tb3_slam` | `roslaunch turtlebot3_slam turtlebot3_slam.launch` | Laptop |
| `tb3_rviz` | `roslaunch tuos_tb3_tools rviz.launch` | Laptop |
| `tb3_world` | `roslaunch turtlebot3_gazebo turtlebot3_world.launch` | Laptop |
| `tb3_sim` | `roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch` | Laptop |
| `tb3_bringup` | `roslaunch tuos_tb3_tools ros.launch` | Robot |
| `src` | `source ~/.bashrc` | Both |

</center>