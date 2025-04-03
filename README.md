# Smart-traffic-management-system-using-machine-learning
This project tries to introduce a new method for traffic Estimation based on vehicle density, which is found to be very efficient method. 
The use of YOLOalgorithm proved to be effective in accurately and quickly identifying and tracking vehicles and the AlexNet could successfully identify the features of the video inclusive of the type, color and size of the vehicles present in the video. Automatically detects and prioritizes emergency vehicles, reducing their travel time.

Algorithm used:YOLO algorithm and Alexnet CNN architecture.

Methodology:

1.YOLO Object Detection Initialization: The process begins with initializing the YOLO-based object detection system.
2.Timer Initialization: A timer is initialized to manage the time allocation.
3.Lane Inputs: The system monitors multiple lanes (Lane 1, Lane 2, Lane 3, Lane 4).
4.Capture Video: Video feed from the selected lane is captured.
5.Video Pre-Processing: The captured video is pre-processed for object detection.
6.YOLO Object Detection: The pre-processed video is fed into the YOLO object detection model to identify objects (e.g., vehicles).
7.Density Calculation: The system calculates the traffic density based on detected objects.Threshold Comparison:If Density is less then threshold:a. Set Priorities: Based on the density, lanes are prioritized.                                                                                                                                                        b. Set Timer: The timer is adjusted based on lane priorities.
8.Loop/Restart: The process restarts, cycling through the lanes continuously.
