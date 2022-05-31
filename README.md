# Face-Recognition

#Introduction

It is basically an attendance system project which uses "Face Recognition" to record attendance.

It also consist Student Management System using MYsql database connected with aws cloud.

It is developed by python3.10 using vscode.


#Requirements

High Speed Internet Connectivity(login system is cloud database based)

RAM=8Gb

screen size= 1530x790(size greater than it can cause changes in UI as it is a desktop application(have a fixed geometry))

Take Sample from the camera in laptop(not webcam). changes to do use web cam:

student.py line 503 //{cap=cv2.VideoCapture(0)} change 0 to 1 to use webcam

face_recognition.py line 149  //{cap=cv2.VideoCapture(0)} change 0 to 1 to use webcam


#Recomended Modules

tkinter, tkcalender

Face Recognition Module, //git clone https://github.com/ageitgey/face_recognition.git

OpenCV// if errors shows for cv2 attribute face use pip install opencv-contrib-python and restart system.

Pillow

MySQL connector


#Installation

clone the full folder and just run the login.py file.


#Configuration

Login by first registering yourself in new user register button and using Email and password to login.


![login page](https://user-images.githubusercontent.com/106368999/171094182-82ae4845-7e32-4b1e-b805-448a06b1e80a.png)


the home screen will be available with 7 buttons. Follow the steps to start your app experience:


![main window](https://user-images.githubusercontent.com/106368999/171094212-21647433-3c1d-41de-a288-bafa4a373cab.png)


Steps:

Click on "student details button", Fill all the details and click on save button, then click on Take sample photo to take sample.


![student](https://user-images.githubusercontent.com/106368999/171094277-07d85fc3-291b-4c18-9683-1bae7cf06da6.png)


Proper light should be there while camera takes sample, close the window after sample is taken aur return to home window.

Click on train data button and train the sample. close the window and click on Face Recognition button.

click on Recognize face and wait till camera opens and recognize you on the details you mentioned earlier.

close the camera window using enter. Close and return to home window.

Open the Attendance details window and click on import csv, then import the "Attendance.csv" file.


![attendance](https://user-images.githubusercontent.com/106368999/171094315-ecb13203-a0d4-43a3-8877-8da00f728692.png)


your attendance is visible, you can also export the details and make a new csv file by export button.

you can update and delete database in "Student Details" by the given buttons.

Can access the other buttons for About developer, support and a exit button.
