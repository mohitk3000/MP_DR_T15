# DRDO UAV Guided UGV challenge
Team: 

## Problem Statement

The problem statement is to map an area via UAV aerial imagery and aid a UGV in navigating a complex static environment. 
This requires the team to map the mountain road in the worlds using a UAV and guide a UGV through the area, navigating across various turns, altitudes, and depth of terrain.



## Steps to Run Locally
1. Follow all the [installation](installation/) steps
1. `cd ~/catkin_ws/src/`
1. `git clone https://github.com/RosFreak/MP_DR_T15`
1. `catkin_make`
1. `cd ..`
1. `sorce devel/setup.bash`
1. `roscd interiit22`
1. `roslaunch interiitt22 drdo_world1.launch`

# Steps for running SITL
Run SITL:

1. `cd ~/ardupilot/ArduCopter/`
1. `sim_vehicle.py -v ArduCopter -f gazebo-iris --console`
