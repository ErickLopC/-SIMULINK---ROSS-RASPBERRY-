### ROSS


# SIMULINK - ROSS

## PUBLISH( ROS(RASBERRY PI) -> SIMULINK)
```
mkdir -p ~/rosS/src
```

```
cd rosS/src/
catkin_create_pkg name std_msgs rospy roscpp
```


## CORRER TODO 

##### PUBLISH ROS(RASBERRY PI) 

1 TERMINAL

```
roscore
```

2 TERMINAL
```
rosrun name program12.py
```

3 TERMINAL

```
rostopic echo /publisherUbuntu
```
