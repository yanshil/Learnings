## Online URDF file loading Demo
https://mymodelrobot.appspot.com

## Pybullet
https://github.com/bulletphysics/bullet3/tree/master/examples/pybullet/examples

## URDF: Link and Frame representation
https://ni.www.techfak.uni-bielefeld.de/files/URDF-XACRO.pdf

## Denavit-Hartenberg convention(DH)
https://www.youtube.com/watch?v=rA9tm0gTln8

## Calculation

https://www.youtube.com/watch?v=vEpxPfCTwe4


## Implementation Practise?
* DH Convention 2.8.2 (Transformation Matrix from frame 0 to frame n)
* Operation form a closed chain manipulator
	* Closed chain cannot be purely implemented with URDF. Add constraint with `createConstraint()`. 
	* See Bullet/examples/pybullet/examples/constraint.py for an example.

## Check_urdf

http://wiki.ros.org/urdf/Tutorials/Create%20your%20own%20urdf%20file

```
sudo apt-get install liburdfdom-tools
```
