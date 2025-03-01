# Solution to MATLAB and Simulink Challenge project <224> Snake-like Robot Modeling and Navigation

Items:

[Program link](https://github.com/Alexan41/Solution-to-MATLAB-and-Simulink-Challenge-project-224-Snake-like-Robot-Modeling-and-Navigatiion-.git)

[Project description link](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Snake-like%20Robot%20Modeling%20and%20Navigation)


# Project details
The project is a snake-like robot that moves through an unfamiliar environment filled with walls, dodging obstacles (walls) it encounters along the way.

The robot is made up of 5 large cylinders in series, whose rod movements in and out move the robot forward.
When the rod of a large cylinder is extended, a small cylinder welded to it and pointing towards the ground also extends its rod, which sinks into the ground and immobilizes the large cylinder. 
The large cylinder then starts to retract its rod, but since it's immobilized, it's the body of the cylinder that moves, and with it the robot.

Obstacles detection is carried out by 3 small spheres, one at the front, and tw0 on each side of the end effector, which act as proximity sensors.
If the sphere at the front encounters an obstacle, the spheres on the side move perpendicular to the snake's trajectory and in opposite directions. 
If any encounters an obstacle, it evaluates the distance of this obstacle to the end effector, which pivots to the side from which the obstacle is furthest away.
If one of the sensors on the side of the end effector comes into contact with an obstacle, the robot pivots to the opposite side to avoid the obstacle.


# How to run section
You will need MatLab-simulink 2021 at least, includind SIMSCAPE.
First open the Matlab-Simulink software then load the vrariables.mat file which contains essentials parameters for modeling the robot.
Then open the simulink file FinalRobot.slx and run the simulation.

# Demo
[This youtube link will take you to a demo video of the robot.](https://youtu.be/pSPs5PRWUxc)
 
