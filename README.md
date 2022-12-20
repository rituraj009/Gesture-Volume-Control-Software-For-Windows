# OpenCV-Project
Gesture Volume Control Software For Windows

## Technologies Used
Python    : Programming language  
OpenCV    : To capture webcam input  
Mediapipe : To detect, track hands  
Pycaw     : To control system volume on Windows  

## Description  
1) In this project I have build a gesture volume control system which will allows us  to control the volume of the computer by just using two fingers.  
2) This software captures your webcam input, detects focal points on your hand like the fingertips and joints and allows us to find the distance between two points.  
3) To build this app we use opencv's python module which allows us to capture video from our web cam, frame-by-frame.  
4) Once the video is captured then MediaPipe is used which provides us a set of already trained machine learning models which allows us to detect hands in a live video. 
5) Then detecting the key points on our hands to detect a gesture and find the distance between tips of two fingers so that we could control system volume.  
  ![image](https://user-images.githubusercontent.com/102078863/208752386-bff35419-7d02-4dbf-ae67-7c4bddafd14d.png)  
7) At last using pycaw on Windows to control the system volume and integrate the two things together so that volume could be controlled by two fingers.

## Installation
1) Python x.x < Python 3.9
2) OpevCV

```bash
  pip install opencv-python
```
4) Mediapipe (pip install will currently not work with versions >= 3.9)

```bash
  pip install mediapipe
```
5) Pycaw (Pyton Core Audio Windows Library)

```bash
  pip install pycaw
```

## How to RUN the PROJECT
### Follow the following steps  
1) Open the python file given in the repo, install all the requirement using pip commands.
2) Make sure web camera is working fine to capture the hand.
3) Slowly take your index finger and thumb to control the volume of the system. 
4) If we increase the distance between the these two fingers --> it will increase the volume.
5) If we decrease the distance between the these two fingers --> it will decrease the volume. 
6) Enjoy :smile:

## KEY CONCEPTS  
### OpenCV
* OpenCV (Open Source Computer Vision) is a free and open-source library of computer vision and machine learning algorithms for image and video processing. It was developed by Intel in 1999 and is now maintained by a community of developers.
