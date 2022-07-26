# Air-Canvas
Computer vision project implemented with OpenCV .
Draw your imagination by just waiving your finger in air .
We will be using the computer vision techniques of OpenCV to build this project.
The preffered language is python due to its exhaustive libraries and easy to use syntax .
Here Colour Detection and tracking is used in order to achieve the objective. 
The colour marker in detected and a mask is produced. 
It includes the further steps of morphological operations on the mask produced which are Erosion and Dilation. 
Erosion reduces the impurities present in the mask and dilation further restores the eroded main mask.

# Algorithm
1.Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2.Prepare the canvas frame and put the respective ink buttons on it. 3.. Adjust the trackbar values for finding the mask of coloured marker.
3.Preprocess the mask with morphological operations.(Erotion and dilation)
4.Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
5.Finally draw the points stored in array on the frames and canvas .


![Screenshot (86)](https://user-images.githubusercontent.com/60617403/181000873-42fcb7c3-0ae3-449c-8687-0b125091a55f.png)




![Screenshot (85)](https://user-images.githubusercontent.com/60617403/181000862-e097dc12-d649-462e-a8ed-bf77e91ef0a8.png)




![Screenshot (84)](https://user-images.githubusercontent.com/60617403/181000849-ecb59170-0819-4c7d-ae98-9409be930bf6.png)
