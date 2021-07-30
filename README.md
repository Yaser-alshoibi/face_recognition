# Face Recognition

In this project, I used OpenCV and other libraries with python to recognise faces in pictures.


# Method of Work

First, I used `pip install` to install these libraries:
- cmake
- dlib
- face_recognition
- numpy
- opencv-python

After that, I made a folder for this project, and inside it I put a folder named 'faces' which I copied photos for different people, each photo labled with the name of the person in the photo, beside 'faces' folder, I put `test.jpg` which is the photo I want to apply face recognition on it, and `face_recognition.py` file which include python code for face recognition.

After running `face_recognition.py` it will open the picture and draw a rectangular around all faces in `test.jpg` photo and labeled the recognised photo with the name of the person, and labled any not recognised faces as 'unknown'.


# Result

<p align="center">
<img src="https://user-images.githubusercontent.com/85786699/127700292-9ba494f1-1188-4f21-8a01-31438a6ff843.PNG" width="600">
</p>
