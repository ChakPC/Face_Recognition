# Face_Recognition
This is a good example of a Machine Learning problem involving K-Nearest Neighbours algorithm and OpenCV library of python.

This project has two parts namely the face data collection part and face recognition part. In first part, frames are captured using the
webcam and haarcascade_frontalface_alt.xml file detects the face in the frame. This detected face is stored as a numpy file by the name
of the person whose face is captured.
In second part, frames are captures using the webcam and faces are detected in these frames similarly. Now, these faces are compared with
the stored faces in form of numpy files using K-Nearest Neighbours Algorithm. The closest match file's name is displayed and the face is 
recognised.

K-Nearest Neighburs Algorithm is analogous to the distance formula. The root squared difference in the training and testing data sorts out
the K Nearest matching cases and a majority vote is taken among these neighbours to denote the class of testing data.

This prototype project may have a lot of industrial applications and has a large scope. 
