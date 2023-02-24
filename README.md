# Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB

## Problem Statement: 
Software development of Bathymetric Map generation using ranges from Doppler Velocity Log for C-Bot

### Developed by
Mr. Akshet Bharat Patel <br>
B. Tech, Mechatronics Engineering, Manipal University Jaipur, Rajasthan. <br>

### Under the guidance of
Mrs. Nagvekar M Surekha, Principal Technical Officer, Marine Instrumentation Division <br>
Mr. Pramod Maurya, Principal Scientist, Marine Instrumentation Division <br>
Dr Raja Rout, Assistant Professor, Manipal University Jaipur <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/logo.jpeg) <br>
NATIONAL INSTITUTE OF OCEANOGRAPHY <br>
Dona Paula, Goa-403 004, INDIA <br>
Period: 1st December 2021 to 31st January 2022 <br>

### Aims and Objectives
#### The aim and objectives for the project titled “Software development of Bathymetric Map generation using ranges from Doppler Velocity Log for C-Bot” are:
1. To plot the bathymetric map of the seabed using the data captured by the Doppler Velocity Log (DVL)
2. To Develop an algorithm for the correction of roll, pitch, and yaw motion of the beams of the DVL
3. To simulate the algorithm and code on ‘uuvsimulator’ (A Gazebo-based package for underwater intervention and multi-robot simulation)
4. To validate the results using Rviz (A 3D visualization tool for ROS applications)
5. To create a ROS package using Python Programming Language. <br>

### Methodology
Since the research work is unpublished, the detailed methodology cannot be revealed. The steps involved in the metholodgy are:
1. Geometrical Representation
2. Algorithm of the Code
3. Running the uuvsimulator
4. Plotting the Bathymetric Map using MATLAB
5. MATLAB Code

### Results and Discussions
After implementing the python code for calculating the adjusted values of the beams of the DVL, the points were visualised using the Rviz which is a 3d visualization tool for ROS applications. It provides a view of your robot model, capture sensor information from robot sensors, and replay captured data. It can display data from camera, lasers, from 3D and 2D devices including pictures and point clouds. <br>
For visualising the results, the Rexrov was teleoperated over the sand dunes of the seabed and visualised using Rviz. The results are shown below:
![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Results.jpeg) <br>
Result of the simulation on Rviz <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/3D%20Coordinates.jpg) <br>
3D Plot of the Bathy Lines <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/NON%20Interpolated%20Mesh.jpg) <br>
Mesh Plot of Original Coordinates <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Interpolated%20Surface.jpg) <br>
Surface Plot of Interpolated Coordinates <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Interpolated%20Mesh.jpg) <br>
Mesh Plot of the interpolated coordinates <br>

### Conclusion
Hence by implementing the Linear Velocity Transformation matrix denoted by 𝑱𝟏(𝜼𝟐), the bathymetric map of the seabed can be calculated by adjusting the roll, pitch, and yaw motion of the vehicle and can be visualised using Rviz. The data extracted from the DVL is then saved to a .csv file from the .bag file and imported into MATLAB for plotting the bathymetry maps of the seabed. <br>

### References
[1] “How is bathymetric data used?,” US Department of Commerce, National Oceanic and Atmospheric Administration. https://oceanservice.noaa.gov/facts/bathyuses.html (accessed Feb. 08, 2022). <br>
[2] N. O. and A. A. US Department of Commerce, “Monitoring Oceans and Coasts,” 2015. https://oceanservice.noaa.gov/observations/monitoring/ (accessed Feb. 08, 2022). <br>
[3] C. A. Wyban, “Tides and Tidal Currents—Guidelines for Site and Energy Resource Assessment,” Tide Curr., pp. 13–25, 2020, doi: 10.2307/j.ctvz0h8mc.7. <br>
[4] L. A. M. Bush, L. Blackmore, and B. C. Williams, “AUV bathymetric mapping depth planning for bottom following splice linear programming algorithm,” Ocean. 2016 MTS/IEEE Monterey, OCE 2016, 2016, doi: 10.1109/OCEANS.2016.7761306. <br>
[5] S. Barkby, S. B. Williams, O. Pizarro, and M. V Jakuba, “A featureless approach to efficient bathymetric SLAM using distributed particle mapping,” J. F. Robot., vol. 28, no. 1, pp. 19–39, 2011. <br>
[6] C. Roman and H. Singh, “A self-consistent bathymetric mapping algorithm,” J. F. Robot., vol. 24, no. 1–2, pp. 23–50, 2007.
[7] C. Kunz and H. Singh, “Map building fusing acoustic and visual information using autonomous underwater vehicles,” J. F. Robot., vol. 30, no. 5, pp. 763–783, 2013, doi: 10.1002/rob.21473. <br>
[8] H. Robinson and P. D. Jarman, “A Navigation System For Underwater Vehicles INTEGRATING DVL AND USBL MEASUREMENTS,” pp. 117–130, 1996, doi: 10.3940/rina.warship.1996.3. <br>
[9] J. W. & SONS, “Guidance and Control of Ocean Vehicles - Thor I. Fossen.pdf.” p. 64, 1994. <br>
[10] M. M. M. Manhães, S. A. Scherer, M. Voss, L. R. Douat, and T. Rauschenbach, “{UUV} Simulator: A Gazebo-based package for underwater intervention and multi-robot simulation,” Sep. 2016, doi: 10.1109/oceans.2016.7761080.<br>

## License
[MIT](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/LICENSE) <br>
© Copyright 2022 Akshet Bharat Patel. <br>
All Rights Reserved <br>

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://akshetpatel.tk/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshetpatel/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Akshet9)

## Feedback
If you have any feedback, please reach out to us at akshet.ap@gmail.com