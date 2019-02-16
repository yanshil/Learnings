# Robotics Notes
## Chapter 1
Joints:
* prismatic
* revolute

DOF: usually 6 in 3D space, 3 for position and 3 for orientation

Workspace: portion of the environment the manipulator's end-effector can access

### Manipulators

* Cartesian (all joints are prismatic)
	* Stright motions
	* + Good mechanical stiffness
	* + High accuracy
	* - Low dexterity
	* Typically electric and occasionally pneumatic
* Cylindrical (first joint is revolute joint)
	* + Good mechanical stiffnes
	* - wrist positioning accuracy decreases as the horizontal stroke increases
	* Hydraulic motors
* Spherical (first and second revolute)
	* - lower mechanical stiffness
	* - positioning accuracy decreases as the radial stroke increases
	* + allow manipulation of objects on the floor
	* Electric motors
* SCARA (all axes of motion are parallel)
	* + high stiffness to vertical loads and compliance to horizontal loads (well-suited to vertical assembly tasks)
	* wrist positioning accuracy decreases as the distance of the wrist from the first joint axis increases
	* Suitable for manipulation of small object
	* electric motors
* Anthropomorphic (three revolute joints)
	* + Most dexterous
	* - the correspondence between the DOFs and the Cartesian space variables is lost
	* wrist positioning accuracy varies inside the workspace
	* electric motors


Open & Close kinematic chain
* parallel geometry: closed-chain geometry
	* + high structural stiffness
	* + high operational speeds
	* - reduced workspace

Locomotion System
* Wheeled mobile robots
	* fixed wheel
	* steerable wheel 
	* caster wheel
* Legged mobile robots

* Differential-drive (Differential wheeled robot)[https://en.wikipedia.org/wiki/Differential_wheeled_robot]
* synchro-drive 
* tricycle
* car-like

## Direct Kinematics
* open: when there is only one sequence of links connecting the two ends of the chain
* closed: when a sequence of links forms a loop.