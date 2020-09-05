# Face_recognition
Attendance project that will use webcam to detect faces and record the attendance live in an excel sheet. 


Step 1: Finding the faces. Using the HOG method (Histogram of Oriented Gradients)

Step 2: Posing and Projecting Faces

dlib lib

Step 3: Encoding Faces

It generates 120 measurements for us (eg: distance between eyes, etc)

Step 4: Finding the person's name from the encoding 





Depend

cmake
dlib=19.18
face-recognition,
numpy
opencv



import cv2
import numpy as np
import face_recognition
