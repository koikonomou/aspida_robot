## Simulation for Aspida robot
For ROS Melodic.


$ cd ~/catkin_ws/src 

$ git clone https://github.com/koikonomou/aspida_robot  
$ git clone https://github.com/koikonomou/rb1_base_common  
$ git clone -b melodic-devel https://github.com/RobotnikAutomation/rb1_base_sim  
$ git clone https://github.com/RobotnikAutomation/robotnik_msgs  
$ git clone -b melodic-devel https://github.com/RobotnikAutomation/robotnik_sensors  
$ git clone -b melodic-devel https://github.com/ros-industrial/universal_robot  
$ cd ~/catkin_ws/src/aspida_robot
$ rosdep install aspida_robot
$ cd ~/catkin_ws  
$ catkin_make

Spawn rviz and gazebo model by running:

$ roslaunch aspida_robot spawn_aspida.launch
