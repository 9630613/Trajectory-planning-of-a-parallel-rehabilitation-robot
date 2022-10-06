# Trajectory planning of a parallel rehabilitation robot
<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/Picture4%20(2).png" width= "500"> 

Throughout the past few decades, various parallel robots, due to their large payload capacity, high stiffness, and accuracy in a safe workspace, have been widely developed for ankle rehabilitation. In this project a 2-UPS/RRR configuration is selected. That is a parallel ankle rehabilitation robot (PARR) with two UPS branches and three rotational joints where P and R denotes the active prismatic and rotational joints, respectively.
The passive control strategy based on trajectory planning is done and robot is simulated in MATLAB SIMULINK MULTIBODY. Moreover, the velocity jacobian matrix is calculated.


# Table of content

1. [Parallel 2-UPS/RRR ankle rehabilitation robot](#Parallel-2-UPS/RRR-ankle-rehabilitation-robot)                                                                                                                     
1. [Mechanical Design Of The Robot](#Mechanical-Design-Of-The-Robot)                                                                                                      
1. [Kinematic Analysis](#Kinematic-Analysis) 
    - [Establishment of the kinematics model](##Establishment-of-the-kinematics-model)
    - [Inverse solution of positions](##Inverse-solution-of-positions)
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

<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/1.png" width= "300"> 

As it mentioned, the ankle is like a spherical joint, so it has 3-DOFs. Therefore, the task space has 3-DOFs of rotational movements, and robot could provides all the movements of the ankle. 
# Kinematic Analysis
## Establishment of the kinematics model
<img src="https://github.com/9630613/Trajectory-planning-of-a-parallel-rehabilitation-robot/blob/main/Images/Picture2.png" width= "500"> 

- The fixed coordinate system is $O_0 − X_{o_0}Y_{o_0}Z_{o_0}$ and the moving coordinate system $O_4 − X_{o_4}Y_{o_4}Z_{o_4}$ are established at the rotation center of the mechanism coinciding at the initial position, along the direction of three rotation axes.

- The coordinate system of the UPS branch is shown where, $O_{1,i} − X_{o_{1,i}}Y_{o_{1,i}}Z_{o_{1,i}}$ is the coordinate system whose origin is at the center of the universal joint with its axis $X_{o_{1,i}}$ coinciding with the first axis of the universal joint and the axis $Y_{o_{1,i}}$ coincides with second axis of the universal joint when the robot is in the initial position, $Z_{o_{1,i}} = X_{o_{1,i}} \times Y_{o_{1,i}}$ .

- $O_{2,i} − X_{o_{2,i}}Y_{o_{2,i}}Z_{o_{2,i}}$ is the coordinate system whose origin $O_{2,i}$ is at the center of the universal joint with its axis Y_{o_{2,i}} coinciding with the second axis of the universal joint, and $Z_{o_{2,i}}$ coincides with the axis of jack, while the axis $X_{o_{1,i}} = Y_{o_{1,i}} \times Z_{o_{1,i}}$ .

- $O_{3,i} − X_{o_{3,i}}Y_{o_{3,i}}Z_{o_{3,i}}$ is the coordinate system whose origin $O_{3,i}$ is at the center of the spherical joint with its three axes parallel to the corresponding axes of $O_{2,i} − X_{o_{2,i}}Y_{o_{2,i}}Z_{o_{2,i}}$.
## Inverse solution of positions




# Velocity Jacobian Matrix
# Simulation Of The Robot In MATLAB SIMULINK MULTIBODY
# Results
