# GCC System Setup

GCC Robotics designs and implements robots to learn skills in computer science, electrical engineering, mechanical engineering, systems engineerging, and manufacturing. The curent lineup of includes

## Life of the Party
4 wheeled rover with custom PDU controlled by joystick and web control. Includes RoboClaw as its MCU, Arduino as the motion controller, bumpers for collision detection, and Spark Fun Thing as a wi-fi bridge to a Web Control Interface (Wilbur). 

## Sparta 
4 wheeled all terrain vehicle with custom PDU controlled by joystick and Intel Nuc. Pending software upgrades to include a ROS based software architecture, GPS, inertial measurement unit, and mounting of LIDAR. Contains the same MCU and controller. 

Pending Issues:
- [ ] Setting ROS Master Node to take command data. 
<pre>Use Wilbur website as initial controller? Deprecate Spark Fun Thing?</pre>
- [ ] Ros based logging system
- [ ] Wifi connectivity to local server
- [ ] Dual Wifi compatibility to allow use of internet while logged into ssh
<pre>Server for gcc robotics? </pre>
- [ ] GPS module for Arduino
- [ ] Doxygen auto generated documentation
- [ ] IMU Ros Node
- [ ] LIDAR mounting
- [ ] Implementation of Protobuf messages


