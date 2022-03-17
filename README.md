# Driver-Drowsiness
This project built using Dlib and OpenCV with Python
as a backend language.The project includes direct
working with the 68 facial landmark detector and
also the face detector of the Dlib library. The 68
facial landmark detector is a robustly trained efficient
detector which detects the points on the human face
using which we determine whether the eyes are open
or they are closed

# Dependencies
Make sure you have Python installed in your system along with cv2, dlib, numpy and imutils.

# Working
<center><img src="https://user-images.githubusercontent.com/57006817/158857409-2cc573ce-45db-454c-9535-af2bd2c94926.png" align="center" height="350"></center>
<ul><li>As you can see the<b> above screenshot</b> where the landmarks aredetected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>
<center><img src="https://user-images.githubusercontent.com/57006817/158858078-3d996d69-77cc-4a18-b92d-5f889fe23782.png" align="center" height="350"></center>
<center><img src="https://user-images.githubusercontent.com/57006817/158858287-c5afc62a-2930-42c0-bdbf-c887dcdc52b6.png" align="center" height="350"></center>
<center><img src="https://user-images.githubusercontent.com/57006817/158858311-32b561e8-7d06-483e-ab04-1cbb42c99147.png" align="center" height="350"></center>
