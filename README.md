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


######Starting and Using
elbek@elbek-virtual-machine:~$  source /opt/ros/foxy/setup.sh
OS_DISTRO was set to 'noetic' before. Please make sure that the environment does not mix paths from different distributions.
elbek@elbek-virtual-machine:~$  ros2 run turtlesim turtlesim_node
[INFO] [1663641213.835052574] [turtlesim]: Starting turtlesim with node name /turtlesim
[INFO] [1663641213.843843646] [turtlesim]: Spawning turtle [turtle1] at x=[5.544445], y=[5.544445], theta=[0.000000]
[INFO] [1663641652.042988255] [turtlesim]: Spawning turtle [turtle2] at x=[1.000000], y=[1.000000], theta=[0.000000]
[WARN] [1663641958.871626326] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.941882, y=11.099703])
[WARN] [1663641958.886837813] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.933865, y=11.119869])
[WARN] [1663641958.903235761] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.925849, y=11.119869])
[WARN] [1663641958.919503554] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.917833, y=11.119869])
[WARN] [1663641958.935489939] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.909817, y=11.119869])
[WARN] [1663641958.950991549] [turtlesim]: Oh no! I hit the wall! (Clamping from [x=3.901801, y=11.11.......
....skipped.........

elbek@elbek-virtual-machine:~$ source /opt/ros/foxy/setup.sh
ROS_DISTRO was set to 'noetic' before. Please make sure that the environment does not mix paths from different distributions.
elbek@elbek-virtual-machine:~$ ros2 run turtlesim turtle_teleop_key
Reading from keyboard
---------------------------
Use arrow keys to move the turtle.
Use G|B|V|C|D|E|R|T keys to rotate to absolute orientations. 'F' to cancel a rotation.
'Q' to quit.

#Nodes,services, topics, and actions
