# ROS Publisher and Subscriber

For testing ROS(Robot Operating System) workload, the program in this repo is referred to following materials
- [ROS tutorial](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28c%2B%2B%29)
- [Source code](https://github.com/ros/ros_tutorials)

### Execution

- Running **ROS core** first

Other ROS processors require to register to **core** processor, which helps to pass message and manage the other processors.

```
### commands to run ROS core

$ rosrun
```
ROS core will listen on port 11311 by default.

- The command format of running ROS processors has following format: `rosrun ROS_PACKAGE COMMAND`

We may check the installed package by:

```
$ rospack list-names 
```

