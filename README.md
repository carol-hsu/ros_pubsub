# ROS Publisher and Subscriber

For testing ROS workload, the program in this repo is referred to following materials
- [ROS tutorial](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28c%2B%2B%29)
- [Source code](https://github.com/ros/ros_tutorials)

### Execution

- There must be a process running as `ROS core`

Other ROS processors register to `core` processor, then they can communicated with each other

```
### commands to run ROS core

$ rosrun

```

- The command format of running ROS processors has following format `rosrun ROS_PACKAGE COMMAND`

We may check the installed package by:

```
$ rospack list-names 
```

