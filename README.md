# FAST_LIO

Pre-requisite:
1) Get Livox-SDK from Github: https://github.com/Livox-SDK/Livox-SDK
2) Get livox_ros_driver from GitHub: https://github.com/Livox-SDK/livox_ros_driver


Clone FAST_LIO repo:
```
cd ~/$A_ROS_DIR$/src
git clone https://github.com/hku-mars/FAST_LIO.git
cd FAST_LIO
git submodule update --init
cd ../..
```

1) Move mapping_mid70.launch to ./FAST_LIO/launch
2) Move mid70.yaml to ./FAST_LIO/config

```
catkin_make
source devel/setup.bash
```
