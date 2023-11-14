# XMachines
[XMachines](https://www.xmachines.ai/) is an Indian Robotics & AI company HeadQuartered in Hyderabad, India which designs and manufactures innovative products infused with Robotics & AI technologies for consumer and enterprise markets.

The company was founded in 2017 to bridge the technology gap that exists in Indian agriculture and later ventured into producing Robots for various other industries. It currently produces AI based Robots for Precision agriculture, Autonomous mobile robots for automating material handling operations in manufacturing & warehouse facilities and Mobile Robot Platforms for Robotics Researchers.

# X100 

[X100](https://www.xmachines.ai/research-platforms) is a UGV platform (Unmanned Ground Vehicle) for mobile [robotics research & development](https://www.xmachines.ai/research-platforms). It comes equipped with an array of latest sensors along with a flexibility to add additional sensors and actuators. Its rugged build quality makes it an ideal tool for venturing into Research & Development of Delivery Robots, Space Robotics, Self Driving Cars, [Agriculture](https://www.xmachines.ai/agricultural-robots), [Material Handling](https://www.xmachines.ai/material-handling) and various other advanced robotics applications

X100 is built out of high quality stainless steel which withstands harshest terrain. 
The lug-tread tires and powerful motors gives X100 ample torque to move in challenging terrain.

## x100_gazebo.

x100_gazebo is ROS package. Using this package you can simulate, controll X100 robot in gazebo.

## Installation

* clone the x100_gazebo into you catkin_ws/src/ 
```
git clone https://github.com/XMachines-ai/x100_gazebo.git
```
* run catkin_make command from catkin_ws folder.

## Usage

```
roslaunch x100_gazebo x100_empty_world.launch
```
