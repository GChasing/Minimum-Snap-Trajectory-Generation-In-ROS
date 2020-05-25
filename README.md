# Minimum-Snap-Trajectory-Generation-In-ROS
Minimum snap trajectory generation 3D in ROS
## 1.Prerequisities
- **ubuntu** 16.04, **ROS** Kinetic.
## 2.Build on ROS
  Clone the repository to your catkin workspace and catkin_make. For example:
```
    cd ~/catkin_ws/src
    git clone https://github.com/HandsomeTong66/Minimum-Snap-Trajectory-Generation-In-ROS.git
    cd ../
    catkin_make
    source ~/catkin_ws/devel/setup.bash
```
## 3.Usage
  Execute command in terminal:
```
    roslaunch waypoint_trajectory_generator test.launch
```
you can give some waypoints using the 3D Nav Goal tool,Each time you press the shortcut key "G", you can add waypoints repeatedly, the waypoint selection method is the same as before: mouse point
Click to confirm the x / y coordinates, hold down the left button to rotate to confirm the yaw angle, and hold down the right button to drag up and down to confirm the z coordinate. Given multiple times
The path path to be optimized appears after waypoint.
(End path given, start trajectory generated flag is given
(A waypoint with z axis less than 0)，finally,the trajectory show on the screen:
  <div align=center>
  <img src="https://user-images.githubusercontent.com/54161710/82772896-396b9180-9e73-11ea-877f-9fc8ff99b893.png" width = "360" height = "360">
  </div>
    
  <div align=center>
  <img src="https://user-images.githubusercontent.com/54161710/82772906-3c668200-9e73-11ea-8b9d-3a8bd1d072c4.png" width = "360" height = "360">
  </div>
  
## 4.Reference
深蓝学院 —— Motion Planning for Mobile Robots
