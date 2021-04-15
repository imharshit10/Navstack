# Navstack
These are the two packages I used for the navstack task. The first package, 'f1tenth sim' is the simulator while, the second package is for the different parameters used in the local planner.


Steps for running after cloning, and the cmake function:

roslaunch f1tenth_simulator simulator.launch 

In a new terminal,
roslaunch f1tenth_simulator gmapping.launch 

In a new terminal,
#[rosrun f1tenth_simulator motion.py]
