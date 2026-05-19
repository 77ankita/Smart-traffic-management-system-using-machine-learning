# Smart-traffic-management-system-using-machine-learning
This project tries to introduce a new method for traffic Estimation based on vehicle density, which is found to be very efficient method. The use of YOLO algorithm proved to be effective in accurately and quickly identifying and tracking vehicles and the AlexNet could successfully identify the features of the video inclusive of the type, color and size of the vehicles present in the video. Automatically detects and prioritizes emergency vehicles, reducing their travel time.

# Algorithm and architecture
YOLO algorithm and Alexnet CNN architecture.

# Language
Python

# Tools
VS Code

# Libraries
* Tkinter
* OpenCV
* PIL
* Frame Analyzer
* Timer Algorithm
  
# Objectives
* To automate traffic signal timing based on vehicle count in each lane.
* Detection of emergency vehicles and set priority of signals.
* Count total number of vehicles in each lane.
* Also counts total number of emergency and non-emergency vehicles.
  
# Methodology
1. YOLO Object Detection Initialization
2. Timer Initialization
3. Lane Inputs the system monitors multiple lanes (Lane 1, Lane 2, Lane 3, Lane 4).
4. Capture Video
5. Video Pre-Processing
6. YOLO Object Detection
7. Density Calculation: The system calculates the traffic density based on detected objects.Threshold Comparison:If Density is less then threshold:a. Set Priorities: Based on the density, lanes are prioritized.                                                                                                                                                     b. Set Timer: The timer is adjusted based on lane priorities.
8. Loop/Restart: The process restarts, cycling through the lanes continuously.

# Output
* The system sets priority for each lane based on Emergency Vehicles and Non-Emergency Vehicles(NEV) and gives priority for emergency vehicles(EV).
* Counts total number of Emegency Vehicles(TEV).
* It also counts the number of emergency vehicles in each lane.
* Based on the density of traffic it alots Estimated Time Required(ETR) for each lane.
* 
