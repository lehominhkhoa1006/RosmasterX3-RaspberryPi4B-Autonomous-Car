# Rosmaster X3 Raspberry Pi 4B Autonomous Car
A ROS 2-based autonomous vehicle project built around the ROSMASTER X3 platform, Raspberry Pi 4B, and YDLIDAR X3, combining physical robot assembly with custom robot modeling and RViz-based simulation.

<p align="center">
  <img src="images/03_robot_completed.png" alt="Completed ROSMASTER X3 Autonomous Car" width="400"><br>
  <em>Figure 1. Completed ROSMASTER X3 platform assembled for the project physical implementation and development.</em>
</p>

## Overview

This project was developed as a group project for the Automotive Electrical and Electronic Systems course at Ho Chi Minh City University of Technology and Education (HCMUTE) during the 2023–2024 academic year.

The project explored an autonomous-car platform built around the ROSMASTER X3, with a Raspberry Pi 4B as the main computing platform and a YDLIDAR X3 as a key sensing component. The group assembled and worked with the physical robot platform, while also developing a ROS 2 robot description and visualization environment for simulation.

The custom ROS 2 package includes a robot model with four mecanum wheels, LiDAR and camera representations, URDF-based robot description, launch configuration, and RViz visualization. The project was demonstrated through both the physical robot platform and a ROS 2/RViz simulation workflow.

## Project Objectives

The project aimed to:

- Explore the architecture and operation of the ROSMASTER X3 autonomous vehicle platform.
- Assemble and work with the physical robot platform and its main hardware components.
- Develop a ROS 2 robot description representing the four-wheel mecanum vehicle and onboard sensor locations.
- Configure a visualization workflow using URDF, robot state publishing, joint state control, and RViz.
- Demonstrate the relationship between the physical robot platform and its ROS 2 simulation model.
