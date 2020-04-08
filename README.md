# RTASK-KB
RTask Knowledge Base

## Dependencies:

- IEEE1872-owl [https://github.com/CloudRobotics-TAMP/IEEE1872-owl.git] [fork of Sandro Fiorini repository: https://github.com/srfiorini/IEEE1872-owl]


## Case studies:

***Scenario 1***: 

![testo alt](/imgs/Scenario1.png "Scenario 1")

- The scenario transports a pay-load consisting of a set of pieces from a starting position (top of a table) to a goal position (docking station far from the table). Two robots participate in the mission: one manipulator robot, equipped with a camera and a gripper, and one mobile robot, with laser scans. The former is fixed in front of the table and it can detect and manipulate objects, but it cannot navigate towards the goal region. The latter is not able to manipulate, but it can move within the environment while avoiding obstacles. Moreover, a container is located on its top, giving the mobile robot the capability of transporting objects from a start pose to a goal. 
- Code: https://github.com/autonomous-robotics-master/ar_arena.git

***Scenario 2***: 

![testo alt](/imgs/Scenario2.png "Scenario 2")

- Two robots (UAV and UGV) populate the environment and the mission is to collect two cubes (green and blue). Both robots have the required capabilities: the UAV is able to fly, manipulate (it has a gripper attached), and perceive its surroundings, while the UGV is able to navigate, manipulate, perceive and scan. However, as seen from the figure, the reachability area of the UGV does not allow it to manipulate the blue cube, hence performs tasks involving green cube only.
- Code: https://github.com/CloudRobotics-TAMP/case_study_2.git
