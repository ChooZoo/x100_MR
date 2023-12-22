# x100_MR
Several packages for ROS (noetic) used for Gazebo simulation of xmachines x100 UGV in a custom world.
More about x100: https://www.xmachines.ai/x100
# prerequisites
Main launch file is using ROS package pointcloud_to_laserscan. 
To install it (noetic version) use:

sudo apt install ros-noetic-pointcloud-to-laserscan

# Usage

Clone files in src folder of your ROS workspace for example:

cd ~/catkin_ws/src
git clone https://github.com/ChooZoo/x100_MR.git

Than run catkin_make from your worskpace:

cd ~/catkin_ws
catkin_make

Run the main launch file using:

roslaunch x100_gazebo x100_world.launch
