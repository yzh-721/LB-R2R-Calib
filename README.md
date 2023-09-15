# LB-R2R-Calib

After calibration, the distribution of radar point clouds is as follows: the red point cloud represents radar 1, the green point cloud represents radar 2, and the center trajectory is marked with larger-sized points.

<img src="https://github.com/yzh-721/LB-R2R-Calib/blob/main/GGPara_z_backgroud.gif" alt="GGPara_z"/>

The registered point cloud trajectories in other scenarios.

<img src="https://github.com/yzh-721/LB-R2R-Calib/blob/main/GGPara.gif" width="500" height="300" alt="GGPara"/>    <img src="https://github.com/yzh-721/LB-R2R-Calib/blob/main/GGPerp.gif" width="500"  height="300" alt="GGPerp"/><br/>
## Introduction
LB-R2R-Calib is a new algorithm to rapidly and robustly locate the target and extract the target center from  very cluttered 4D radar point cloud, based on an important observation of the 4D radar.
### Motivation
In Vehicle-to-Everything (V2X), Roadside Perception Unit (RSU) is an important component to improve the perception ability for unmanned vehicles. Moreover, fusing multiple RSU sensors can further improve the perception by extending the Field-of-View (FOV) and avoiding blind spots. 
### Experimental Results
First row: setup of the four datasets with different baseline and viewpoint-difference. The four configurations represent  typical scenarios: two radars' viewpoint is perpendicular (Perp), opposite (Opp), and parallel (Para).  

Second row: the registered raw point cloud. The zoomed-in part is the target viewed from two radars. 

Third row: the registered target centers detected from two radars.  

Fourth and fifth row: registered point cloud of a human walking in front of the two radars. The human is holding the target. 

![Image text](https://github.com/yzh-721/LB-R2R-Calib/blob/main/fig_qualitative.png)
