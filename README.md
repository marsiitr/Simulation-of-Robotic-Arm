# Simulation-of-Robotic-Arm

## Abstract
This project involves the creation of a MATLAB simulation of a 6 Degree of Freedom (DOF) robotic arm. The project starts with the creation of a CAD model of the robotic arm, which is then exported to MATLAB. The simulation is performed using Simscape, a MATLAB tool for modeling and simulating physical systems. The simulation aims to demonstrate the movement of the robotic arm and its capabilities in performing different tasks. This project provides an opportunity to gain hands-on experience in CAD modeling and MATLAB simulation, while also enhancing understanding of the principles of robotics and mechanical systems.

## Motivation
The motivation for this project is to create a MATLAB simulation of a 6 DOF robotic arm using CAD modeling and Simscape simulation. This project provides an opportunity to gain practical experience and insight into the capabilities and limitations of robotic arms, as well as enhancing understanding of the principles of robotics and mechanical systems.

## Working

The 6 Degree of Freedom (DOF) robotic arm simulation in MATLAB involves using two algorithms - **forward kinematics** and **inverse kinematics** - to determine the position and orientation of the robotic arm in the 3D world space. Forward kinematics calculates the end effector's position and orientation using the joint angles, while inverse kinematics computes the joint angles needed to achieve a specific end effector position and orientation.

To simulate the robotic arm in MATLAB, we use the inbuilt algorithm from **Peter Corke's Robotic Toolbox**, which provides functions like **fkine** (for forward kinematics) and **ikine** (for inverse kinematics). The serial link and link functions are used to create the robotic arm in the 3D plot. Since the **Simscape Multibody export** option is not available in Solidworks in our cracked version, we could not export the CAD model of the robotic arm from Solidworks to MATLAB and simulate the robotic arm directly from Solidworks. Instead, we use the inbuilt algorithms to simulate and plot it.

Additionally, we create a user interface (**GUI**) for both the inverse and forward functions to make it easier to operate the simulation. The GUI allows the user to input the desired position and orientation of the robotic arm and displays the joint angles needed to achieve it. This helps in visualizing the movement of the robotic arm and understanding how it works. Overall, this simulation provides a practical way to explore the capabilities and limitations of robotic arms in a virtual environment, and the use of MATLAB and its tools helps in gaining valuable skills and knowledge in robotics and engineering.

## CAD Model

The CAD model of a **6 DOF** robotic arm in Solidworks is a virtual 3D model that represents the physical structure of the robotic arm. The model consists of individual parts that are assembled together to form the complete arm, and each part is defined by its geometric shape, dimensions, and material properties. The CAD model is used as a basis for simulation and analysis of the robotic arm's behavior, including kinematics and dynamics.

![**CAD Model**](https://i.imgur.com/4zyuMiQ.png)

Regarding the **end effector**, the reason for not using a magnetic end effector and instead using an iron end effector could be to provide better stability and control. Iron end effectors have a higher mass compared to magnetic end effectors, which can help in maintaining stability and providing a better grip while handling heavy objects. Additionally, iron end effectors can be magnetized if necessary, providing a similar function to magnetic end effectors. Ultimately, the choice of end effector depends on the specific application and requirements of the robotic arm.
![enter image description here](https://i.imgur.com/UdlgF3n.jpg)

## Simulation in MATLAB

The simulation of a 6 DOF robotic arm using a CAD model in Solidworks is a tool for testing and optimizing the arm's movements before it's actually built. Incorporating **forward and inverse kinematics** using the **Peter Corke Robotic Toolbox ensures that the arm's movements are accurate and realistic. This is because the toolbox takes into account the complex relationships between the arm's joints and the movements of the end effector.
![enter image description here](https://i.imgur.com/cHS31ZF.png)

The addition of a GUI to the simulation makes it more user-friendly and accessible. The GUI takes joint space input and gives world space output, and vice versa. This allows users to easily interact with the simulation and test different scenarios and movements without requiring a deep understanding of the underlying mathematics and programming.

Overall, this simulation is a valuable tool for testing and optimizing 6 DOF robotic arms for a variety of applications. It allows engineers and designers to visualize the arm's behavior in a virtual environment and make adjustments before building a physical prototype. This can save time and resources, as well as lead to a more optimized and effective design.

## Tech Stack

- Solidworks 2019
- MATLAB
- Peter Corke Robotic MATLAB Toolbox

## Application
- **Industrial Automation**: The 6 DOF robotic arm can be used in manufacturing processes for assembling, welding, and material handling.
- **Medical Robotics**: The simulation of a 6 DOF robotic arm can be useful for medical applications such as surgery, rehabilitation, and prosthetics.
- **Aerospace and Defense**: The simulation of a 6 DOF robotic arm can be used for space exploration and satellite servicing, as well as for handling hazardous materials in defense applications.
- **Research and Development**: The simulation of a 6 DOF robotic arm can be used for testing and prototyping new robotic systems, control algorithms, and sensor technologies.
## Limitations

- The simulation may not take into account constraints such as friction, gravity that can affect the behavior of the robotic arm.
-  The simulation may not accurately model the behavior of the control system used to operate the robotic arm.
- The simulation may not accurately model the dynamics and kinematics of the actual physical system.
- This may not accurately model the geometry and material properties of the robotic arm components.

## Future Improvements
- Use of Virtual Sensors and Controller for real-time constraint movement of the Arms of robotic Model.
- The MATLAB simulation could be integrated with other software and hardware, such as CAD software or sensors, to provide a more complete and integrated system.
- Improving the calibration of the arm's sensors, optimizing the control algorithms, and increasing the resolution of the actuators.

## Team Members
1. [Khushi Agarwal](https://github.com/epiceexii-0621)
2. [Hardik](https://github.com/Apocalypse-0729)
3. [Shubham Tambe](https://github.com/shubhz9922)
4. [Prateek Prakash](https://github.com/PratikSanap)
## Mentor
- Nagesh Bansal

## References
- [6 DOF  Robotic Arm Tutorial for Beginners](https://www.youtube.com/watch?v=hV3Ha0bWDgI)
- [Petercorke MATALB Robotic ToolBox](https://petercorke.com/toolboxes/robotics-toolbox/)
- [Denavit HartenBerg's Parameter](http://www-scf.usc.edu/~csci545/slides/Lect5_Forward-InverseKinematicsII_Short.pdf)
- [MATLAB GUI](https://www.mathworks.com/discovery/matlab-gui.html)
