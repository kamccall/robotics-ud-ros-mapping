# robotics-ud-ros-localization
udacity robotics project4 using rtab-map on simulated gazebo robot to create 2d and 3d environment maps.
this project focused on doing SLAM using the ROS `RTAB` package which uses graphSLAM to create a map of the `gazebo` world used in prior projects.  

this is an image of the mapping process underway using `RTAB`, while using the python teleop package to drive the robot around the `gazebo` world. 
![image](https://user-images.githubusercontent.com/19736497/201530667-2e359f02-795a-4332-8887-bc3de2a21561.png)![image](https://user-images.githubusercontent.com/19736497/201534281-c75c5661-6a22-411f-a6ca-226db86dbf02.png)


after mapping the entire environment, the `RTAB` package places a (very large) rtab database file in the `/root/.ros` directory.  this is an image of the resulting map (far left) generated while viewing it within the `rtabdatabaseViewer` utility. 
![image](https://user-images.githubusercontent.com/19736497/201499350-23f0037c-ade2-43a0-bf55-853506e5c07b.png)![image](https://user-images.githubusercontent.com/19736497/201499704-2f061738-75b4-4f9f-a3a8-e0c4107be3ac.png)


as you may be able to see in the diagram (it is quite small), after several laps around the condo there was only 1 loop closure, so i re-ran the mapping utility and did more laps to secure more loop closures (now 6).  however, this made the rtab database over 200 MB (152 MB even in zipped form).  
![image](https://user-images.githubusercontent.com/19736497/201531924-22e62ee1-ebf7-4a61-9f17-34a97ebf4616.png)![image](https://user-images.githubusercontent.com/19736497/201534898-61403611-f360-452c-a8ad-9ef89e346390.png)
![image](https://user-images.githubusercontent.com/19736497/201532019-57a3006b-9681-4610-b2f6-e35207e2cfd4.png)![image](https://user-images.githubusercontent.com/19736497/201534911-ffcc3178-03f6-49be-a084-ff86d52f8ac0.png)

i was able to download the rtab database file and put it into onedrive, which can be accessed here:  https://1drv.ms/u/s!AvaOO0ayi_lviPVhYCfoDumBjtaA8Q?e=JFwXMI
