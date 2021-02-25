# HW OSL Wavetank Simulation
## Requirements
- ROS Installation
- ROS Gazebo 

## Running The Simulation
The simulation demo uses a Logitech FX10 to controlt he BlueROV2 In one terminal load the world in Gazebo

```bash
roslaunch orca_worlds osl_wavetank.launch
```

and in other temrinal load the BlueROV2 into Gazebo

```bash
roslaunch bluerov2_gazebo start_pid_controller_demo.launch
```
