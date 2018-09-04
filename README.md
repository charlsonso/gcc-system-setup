# GCC System Setup

GCC Robotics designs and implements robots to learn skills in computer science, electrical engineering, mechanical engineering, systems engineerging, and manufacturing. The curent lineup of includes

## Life of the Party
4 wheeled rover with custom PDU controlled by joystick and web control. Includes RoboClaw as its MCU, Arduino as the motion controller, bumpers for collision detection, and Spark Fun Thing as a wi-fi bridge to a Web Control Interface (Wilbur). 

![alt text](https://raw.githubusercontent.com/so0p/gcc-system-setup/master/images/lotp-system.png)

## Sparta 
4 wheeled all terrain vehicle with custom PDU controlled by joystick and Intel Nuc. Pending software upgrades to include a ROS based software architecture, GPS, inertial measurement unit, and mounting of LIDAR. Contains the same MCU and controller. 

## To-Do:
- [ ] Internet connectivity while local server while on 
- [ ] Dual Wifi compatibility to allow use of internet while logged into ssh
<pre>Server for gcc robotics? </pre>
- [ ] GPS module for Arduino
- [ ] auto generated documentation
- [ ] IMU Ros Node
- [ ] LIDAR mounting
- [ ] Implementation of Protobuf messages?
- [ ] Organize libariries to fit into Arduino
- [ ] Watchdog

## List of GCC Software Modules
#### [gcc-motor-control](https://github.com/so0p/gcc-motor-control)
Arduino Controller
#### [gcc-wifi-bridge](https://github.com/so0p/gcc-wifi-bridge)
Spark Fun Thing Wifi Bridge
#### [gcc-web-control](https://github.com/so0p/gcc-web-control)
Web Interface for Rover
#### [gcc-joystick](https://github.com/so0p/gcc-joystick)
Joystick Controller
#### [gcc-command-server](https://github.com/so0p/gcc-command-center)
ROS Node Library for ROVER OS
