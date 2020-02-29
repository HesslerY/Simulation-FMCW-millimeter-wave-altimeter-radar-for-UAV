# Simulation-of-millimeter-wave-altimeter-radar-for-UAV
# This porject is not funned by any ognization. It is developed for study purpose.
#
This is a simple simulation of millimeter wave altimeter radar for UAV
scenario: When UAV is flying in the sky, the ground is the detection object. 
#
[This simulatin can help you under the signal features of a UAV altimeter radar.]
1. The simulation generates signal data of millimeter-wave-altimeter-radar-for-UAV. 
2. High resolution ranging algorithm is provided to detect the distance between the UAV and the Ground.
#

# How to run the simulation:
Download all files. 
1. step 1: run fangdi_24G.m to generate simulated signal data (opitonal step). Make sure your matlab installtion includes Phased Array System Toolbox. # Skip this step and just run step 2, if your matlab doesn't have Phased Array System Toolbox.
2. step 2: run fangdi_32x32rdm_high_resolution_range_velocity.m for ranging alorithm.
3. Change target_xpos in fangdi_24G.m to change the ground distance from UAV, and re-run steps 1 and 2. Make sure your matlab installtion includes Phased Array System Toolbox. # Skip this step and just run step 2, if your matlab doesn't have Phased Array System Toolbox.

#
Author: Lin Junyang
Email : liynjy@163.com
WeChat: liynjy 
Date : 2020-2-29
All Rights Reserved.
