[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-SLAMLab-Private
In this lab, you’ll implement a gmapping ROS package which is based on the Grid-based FastSLAM algorithm to map an environment.

### Steps to launch the simulation:
Launch the simulation in the VM machine provided in Term1. 

#### Step 1 Create a catkin workspace:
Skipt this step if you already have a workspace
```sh
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/src
$ catkin_init_workspace
$ cd ..
$ catkin_make
```

#### Step 2 Perform a system update:
```sh
$ sudo apt-get update
```

#### Step 3 Clone the package in src:
```sh
$ cd ~/catkin_ws/src
$ git clone https://github.com/udacity/RoboND-SLAMLab-Private
```

#### Step 4 Build and source your workspace:
```sh
$ cd ..
$ catkin_make
$ source devel/setup.bash
```

#### Step 5 Launch the nodes:
```sh
$ cd src/RoboND-SLAMLab-Private
$ ./SLAM.sh
```
Now, you should see Gazebo and rviz launching.

### End Result:
In the terminal, use the keyboard commands(u-i-o-j-k-l-m-,-.) and drive the robot around. You'll see a map of the environment in Rviz! 
![alt text](Images/Output.png)
