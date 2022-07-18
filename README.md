# ROS-Installation-and-Setup
Task one for smart methods summer internship, AI and Robotics field of practice
Smart Methods AI Task One - ROS Insulation 
Bahaa Hammad

ROS is preferred to run on Linux OS, thus, the installation is split into two parts. 
First, installing Linux. Second, installing ROS on Linux. 

Installing Linux – Ubuntu 20.04: 
ROS Noetic is supported by Ubuntu 20.04

Start by installing a Virtual Machine to run Linux. I choose Oracle VM. https://www.virtualbox.org/wiki/Downloads

Then, download ubuntu, which is one of the Linux distributions.
https://ubuntu.com/download/alternative-downloads

Finally, put they both together by following the steps on the ubuntu website to set up ubuntu on the virtual machine. 
https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview









Installing ROS – Noetic: 

By following Neotic documentation to install ROS on ubuntu 20.04. 
http://wiki.ros.org/noetic/Installation/Ubuntu

Due to a security incident, apt update fails to work, by stating that the key to a repo is unavailable.
The old key has been revoked as part of the measures to deal with a recent security incident. 
Through research, I found an article that solves the problem by providing the new keys. 

https://answers.ros.org/question/325039/apt-update-fails-cannot-install-pkgs-key-not-working/




To run ROS, “roscore” must be typed every time in the terminal.

To avoid typing “ source /opt/ros/noetic/setup.bash ” every time opening the terminal, used the  “ echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc ” command.

For future package installations, use:
sudo apt install ros-noetic-PACKGENAME  

Now ROS Noetic is installed on Ubuntu 20.04 and running. 


