# multibot
ROS2 Multi-Robot Package
Version: Foxy

## How to Use
#### 1. Navigate into the source directory and clone Git
```shell script
mkdir -p ~/"YOUR_WS"/src
cd ~/"YOUR_WS"/src
git clone --recursive "GIT_HTTPS"
```
#### 2. Build
```shell script
cd ..
colcon_build
source install /setup.bash
```
#### 3. Launch Server
 ```shell script
ros2 launch multibot_server multibot_server_launch.py 
```

#### 4. Open another terminal and launch Robot
 ```shell script
ros2 launch multibot_robot robot1_simul_launch.py 
```