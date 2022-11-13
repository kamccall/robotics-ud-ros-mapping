# robotics-ud-ros-localization
udacity robotics project4 using rtab-map on simulated gazebo robot to create 2d and 3d environment maps.
this project focused on doing SLAM using the ROS `RTAB` package which uses graphSLAM to create a map of the `gazebo` world used in prior projects.  

this is an image of the mapping process underway using `RTAB`, while using the python teleop package to drive the robot around the `gazebo` world. 
![image](https://user-images.githubusercontent.com/19736497/201499040-ab312347-6ceb-48b2-af47-b6a0363ec078.png)![image](https://user-images.githubusercontent.com/19736497/201499651-db6e7dea-17e2-44f0-975d-c50f6b3456a3.png)

after mapping the entire environment, the `RTAB` package places a (very large) rtab database file in the `/root/.ros` directory.  this is an image of the resulting map (far left) generated while viewing it within the `rtabdatabaseViewer` utility. 
![image](https://user-images.githubusercontent.com/19736497/201499350-23f0037c-ade2-43a0-bf55-853506e5c07b.png)![image](https://user-images.githubusercontent.com/19736497/201499704-2f061738-75b4-4f9f-a3a8-e0c4107be3ac.png)
