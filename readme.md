# Hypha ROS RaceCar pkg
  
$ sudo apt-get install remmina synaptic gimp  
$ sudo apt-get install ros-indigo-navigation -y  
$ sudo apt-get install ros-indigo-hector-slam ros-indigo-hector-mapping -y  
$ sudo apt-get install arduino  
$ sudo apt-get install ros-indigo-rosserial-arduino  
$ sudo apt-get install ros-indigo-rosserial  
$ sudo apt-get install ros-indigo-slam-gmapping   
$ sudo apt-get install ros-indigo-mrpt-slam ros-indigo-mrpt-icp-slam-2d  
   
   
create your own catkin_ws (http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment#Create_a_ROS_Workspace)  
$ cd catkin_ws/src  
$ git clone https://github.com/cra-ros-pkg/robot_localization.git  
	git checkout indigo-devel  
$ git clone https://github.com/ros-planning/navigation_tutorials.git  
$ git clone https://github.com/MAPIRlab/mapir-ros-pkgs.git  
$ git clone https://github.com/Hypha-ROS/hypha-racecar  
