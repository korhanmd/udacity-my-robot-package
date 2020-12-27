# `my_robot` Package

This is the `my_robot` package of [Go Chase It!](https://github.com/korhanmd/udacity-go-chase-it) project (second project of Udacity's Robotics Software Engineer Nanodegree).
It includes robot and world definitions and launch files.

To use you need to create catkin workspace first, if it doesn't exist. To create it, go to the directory you want to create workspace and write commands below to the terminal.

```
$ mkdir -p catkin_ws/src
$ cd catkin_ws/src
$ catkin_init_workspace
```

Then create `my_robot` package with commands below inside src folder of the workspace.

```
$ catkin_create_pkg my_robot
```

Copy the content of this repository inside `my_robot` directory. Then go to the root folder of your workspace. Use the commands below to build sources and load robot and the world.

```
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```
