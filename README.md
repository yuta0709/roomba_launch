# Roomba_launch

## Requirements
- libcreate
- create_robot
- rplidar_ros

### libcreate
```:console
git clone https://github.com/AutonomyLab/libcreate.git
cd libcreate
mkdir build && cd build
cmake ..
make -j
sudo make install
```

### create_robot

```:console
cd ~/catkin_ws/src
git clone https://github.com/AutonomyLab/create_robot.git
cd ..
catkin_make
```

## rplidar_ros

```:console
cd ~/catkin_ws/src
git clone https://github.com/Slamtec/rplidar_ros.git
cd ..
catkin_make
```

## Usage