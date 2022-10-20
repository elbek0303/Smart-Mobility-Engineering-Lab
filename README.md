# Smart-Mobility-Engineering-Lab
This repository for Smart Mobility Engineering Lab class 

##### WEEK 4 ########
1. Installing Turtlesim

elbek@elbek-virtual-machine:~$ sudo apt update
[sudo] password for elbek: 
Hit:1 http://security.ubuntu.com/ubuntu jammy-security InRelease
Hit:2 http://kr.archive.ubuntu.com/ubuntu jammy InRelease
Hit:3 http://kr.archive.ubuntu.com/ubuntu jammy-updates InRelease
Hit:4 http://kr.archive.ubuntu.com/ubuntu jammy-backports InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
170 packages can be upgraded. Run 'apt list --upgradable' to see them.


![image](https://user-images.githubusercontent.com/65524183/196971741-d0e0bcb6-5425-4198-86ea-c8dbe9495fad.png)

elbek@elbek-virtual-machine:~$ sudo apt install ros-foxy-turtlesim
Reading package lists... Done
Building dependency tree       
Reading state information... Done
ros-foxy-turtlesim is already the newest version (1.2.5-1focal.20220209.151154).
0 upgraded, 0 newly installed, 0 to remove and 26 not upgraded.
elbek@elbek-virtual-machine:~$ source /opt/ros/foxy/setup.sh
ROS_DISTRO was set to 'noetic' before. Please make sure that the environment does not mix paths from different distributions.
elbek@elbek-virtual-machine:~$  ros2 pkg executables turtlesim
turtlesim draw_square
turtlesim mimic
turtlesim turtle_teleop_key
turtlesim turtlesim_node
