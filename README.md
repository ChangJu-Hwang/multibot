# multibot
ROS2 Multi-Robot Package
Version: Foxy

## How to Use
### 1. Navigate into the source directory and clone Git
```shell script
git clone --recursive https://github.com/ChangJu-Hwang/multibot.git
```
### 2. Build
```shell script
cd ..
colcon_build
source install /setup.bash
```
### 3. Launch Server
* #### 3-1. Real Robot: ISR M2
>```shell script
> ros2 launch multibot_server multibot_server_launch.py 
> ```
* #### 3-2. Gazebo Simulation
>```shell script
>ros2 launch multibot_server multibot_server_simul_launch.py 
>```
### 4. Open another terminal and launch Robot
* #### 4-1. Real Robot: ISR M2
>```shell script
>ros2 launch multibot_robot robot1_launch.py
>```
* #### 4-2. Gazebo Simulation
>```shell script
>ros2 launch multibot_robot robot1_simul_launch.py
>```