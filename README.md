# Motion-detector-using-OpenCV-and-pandas
Detection of any motion or movement of an object using the webcam and giving the interval of presence and absence 

Libraries used-
|<img src="/Opencv.png">|<img src="/Pandas.png">
In this project we use the OpenCv library to capture the first frame of the object in the detector, by capturing the first frame we take the initial postion of the object and then we observe the motion of the object by four frames-
1-Gray frame
2-Difference frame
3-Threshold frame
4-Color frame
Four effects are there because-
The lower 2 effects are giving the change in motion with respect to the 1st frame 
The upper has an grayscale frame and an coloured vedio or RGB frame

The greyframe is for normal visualisation and the coloured frame for object detection process showing rectangles in objects

The time can be recorded for the change of motion using the code modified as
<img src="/Time for motion detector.png">
