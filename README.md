# robotics-ud-ros-localization
udacity robotics project3 using amc package to perform localization within gazebo world.
this project focused on creating a map (of the gazebo world used in prior projects) using map_server to create the map.pgm representation, and then the use of the amcl ROS package in order to create a particle cloud to localize the robot within that mapped environment while it navigates using rviz. 

this initial image is the robot within both the gazebo world as well as the rviz visualization tool. 
![image](https://user-images.githubusercontent.com/19736497/200440496-58044ee3-c327-4812-ab72-0f2833b3804f.png)![image](https://user-images.githubusercontent.com/19736497/200444151-8dff8f24-2857-4bef-b140-18f5840728c0.png)


this is a more detailed image of the initial particle cloud created by the amcl package within rviz before navigation.
![image](https://user-images.githubusercontent.com/19736497/200440641-b975da29-5d02-4a62-b938-b01bafb06a2e.png)![image](https://user-images.githubusercontent.com/19736497/200444410-5b1cc6e3-6d4f-4b20-bc01-7c281f25ac2f.png)

these are more detailed images of the robot while underway, navigating using the 2d-navigation in rviz. 
 ![image](https://user-images.githubusercontent.com/19736497/200443174-227708b0-f0c9-4256-87fd-9ba8f58a8002.png)
![image](https://user-images.githubusercontent.com/19736497/200443367-f97f6525-8a67-4d49-a455-6d98410c0653.png)![image](https://user-images.githubusercontent.com/19736497/200444505-2a941b73-a11f-4c3e-97e8-ae91f4e11404.png)



