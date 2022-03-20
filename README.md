# Human-Center-Robotics-Lab-Internship

# Matlab Setup and Scaling
A scaling factor to obtain dimensionalized coordinate values from the pixel coordinates. The scaling factor (s) was calculated as: 𝑠 = 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑒 / 𝑝𝑖𝑥𝑒𝑙 𝑙𝑒𝑛𝑔𝑡ℎ.

Distance between two strips of tapes on the floor at each end of the walkway that ran parallel to the viewpoints of cameras C1 and C3. Pixel length was taken as the horizontal pixel length between the midpoints of each strip of tape. 
 1) calculating individual scaling factors from each participant based on the horizontal distance traversed by left and right ankle markers in motion capture data and left and right ankle keypoints in OpenPose data;
2) calculating the distance between the strips of tape for each individual participant;
3) calculating the ensemble mean distance. The ensemble mean distance was 6.30 m and they used this fixed value to calculate scaling factors for each individual participant.
