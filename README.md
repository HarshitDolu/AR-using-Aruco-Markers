# AR-using-Aruco-Markers
ArUco stands for Augmented Reality University of Cordoba. That is where it was developed in Spain. An aruco marker is a fiducial marker that is placed on the object or scene being imaged. It is a binary square with black background and boundaries and a white generated pattern within it that uniquely identifies it. The black boundary helps making their detection easier.<br>
<p align="center">
  <img width="460" height="300" src="https://github.com/HarshitDolu/AR-using-Aruco-Markers/blob/main/marker_1.png">
</p>

They can be generated in a variety of sizes. The size is chosen based on the object size and the scene, for a successful detection. If very small markers are not being detected, just increasing their size can make their detection easier.




The idea is that you print these markers and put them in the real world. You can photograph the real world and detect these markers uniquely.

 In a robotics application, you can put these markers along the path of the warehouse robot equipped with a camera. When the camera mounted on the robot detects one these markers, it can know its precise location in the warehouse because each marker has a unique ID and we know where the markers were placed in the warehouse.<br>
 
We can generate these markers very easily using OpenCV. The aruco module in OpenCV has a total of 25 predefined dictionaries of markers. All the markers in a dictionary contain the same number of blocks or bits(4×4, 5×5, 6×6 or 7×7), and each dictionary contains a fixed number of markers(50, 100, 250 or 1000).

In this project, simple application of Aruco markers is depicted.
First install, opencv-contrib-python.In this module aruco library is present.
The task is to overlay images (present in markers folder) over aruco markers.
Each image has image no and aruco markers have its unique ID. So overlaying image over aruco when (imageNo == marker_id)

Aruco generator:- <a href="https://chev.me/arucogen/">https://chev.me/arucogen/</a><br>
OpenCV Aruco documentation:- <a href="https://docs.opencv.org/master/d5/dae/tutorial_aruco_detection.html">https://docs.opencv.org/master/d5/dae/tutorial_aruco_detection.html</a>

<p align="center">
   <img width="460" height="300" src="https://github.com/HarshitDolu/AR-using-Aruco-Markers/blob/main/123.png">
  <img width="460" height="300" src="https://github.com/HarshitDolu/AR-using-Aruco-Markers/blob/main/demo.jpeg">
 </p>
 
 
 
