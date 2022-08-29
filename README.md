# ROS2

This project is the OAKD Camera Implementation for ROS2 

## Requirements

1. ROS2 version Galactic
2. Ubuntu version >=18.0.0
3. Python3
4. Depthai installed 
      Check the link for installation guidelines - [Link](https://github.com/luxonis/depthai)
      

## Implementation

1. Open a terminal in the respective main folder 
2. Run the setup bash

```bash
. install/setup.bash
```

3. Run the local setup bash 

```bash
. install/setup.bash
```

4. Build the oakd package

```bash
colcon build --packages-select oakd
```


## Node 

1. Run nodes by "ros2 run oakd <<node_name>>"


2. Main Node - (RGB Video and IMU details both) "ros2 run oakd oakd_main"

```bash
ros2 run oakd oakd_main
```
3. RGB camera node

```bash
ros2 run oakd oakd_rgb
```

4. IMU details 

```bash
ros2 run oakd oakd_imu_rotation
```

```bash
ros2 run oakd oakd_imu_rotation
```

5. Stereo camera ""

```bash
ros2 run oakd oakd_stereo
```

      
      
   
