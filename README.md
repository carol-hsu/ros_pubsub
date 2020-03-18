# ROS Publisher and Subscriber

For testing ROS(Robot Operating System) workload, the program in this repo is referred to following materials
- [ROS tutorial](http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28c%2B%2B%29)
- [Source code](https://github.com/ros/ros_tutorials)

## Execution

- Running **ROS core** first

Other ROS processors require to register to **core** processor, which helps to pass message and manage the other processors.

```
### commands to run ROS core

$ roscore
```
ROS core will listen on port 11311 by default.

- The command format of running ROS processors has following format: `rosrun ROS_PACKAGE COMMAND`

We may check the installed package by:

```
$ rospack list-names 
```

- Running pubsub demo

1. run core processor
2. run sub processor
```
$ rosrun roscpp_tutorials listener
```
3. run pub processor
```
$ rosrun roscpp_tutorials talker
```

## Run pubsub on Kubernetes

1. Build container images and push to private registery

2. Run Kubernetes configuration file
