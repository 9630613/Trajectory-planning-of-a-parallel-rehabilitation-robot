# Trajectory planning of a parallel rehabilitation robot
<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/robot2.png" width= "500"> 

Throughout the past few decades, various parallel robots, due to their large payload capacity, high stiffness, and accuracy in a safe workspace, have been widely developed for ankle rehabilitation. In this project a 2-UPS/RRR configuration is selected. That is a parallel ankle rehabilitation robot (PARR) with two UPS branches and three rotational joints where P and R denotes the active prismatic and rotational joints, respectively.
The passive control strategy based on trajectory planning is done and robot is simulated in MATLAB SIMULINK MULTIBODY. Moreover, the velocity jacobian matrix is calculated.


# Table of content

1. [Parallel 2-UPS/RRR ankle rehabilitation robot](#Parallel-2-UPS/RRR-ankle-rehabilitation-robot)                                                                                                                     
1. [Mechanical Design Of The Robot](#Mechanical-Design-Of-The-Robot)                                                                                                      
1. [Kinematic Analysis](#Kinematic-Analysis) 
1. [Inverse Position Solution](#Inverse-Position-Solution)

1. [Velocity Jacobian Matrix](#Velocity-Jacobian-Matrix)
1. [Simulation Of The Robot In MATLAB SIMULINK MULTIBODY](#Simulation-Of-The-Robot-In-MATLAB-SIMULINK-MULTIBODY)
1. [Results](#Results)


# Parallel 2-UPS/RRR ankle rehabilitation robot
The movement of ankle joint has 3-DOFs, including Dorsiflexion/Plantarflexion (DO/PL), Inversion/Eversion (IN/EV), and
Abduction/Adduction (AB/AD).
In order to prevent harming the ankle, the rotation center of robot should coincide with that of the ankle joint approximately when the patient puts the affected foot onto the upper platform of PARR. 

<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/robot%204.png" width= "300"> 



# Mechanical Design Of The Robot
The mechanical structure of 2-UPS/RRR parallel ankle rehabilitation robot is as in Figure, where, U, P, S and R stand for universal,
prismatic, spherical and revolute joint, respectively. P and $R_1$ represent the actuated joint. The mechanism consists of one
fixed base, one moving platform, two UPS branched chains and one series RRR constrained branch, and it has 3-DOFs with its three rotation axes orthogonal to one point.

<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/robot1%20(2).png" width= "300"> 

As it mentioned, the ankle is like a spherical joint, so it has 3-DOFs. Therefore, the task space has 3-DOFs of rotational movements, and robot could provides all the movements of the ankle. 
# Kinematic Analysis


# Velocity Jacobian Matrix
# Simulation Of The Robot In MATLAB SIMULINK MULTIBODY
# Results
