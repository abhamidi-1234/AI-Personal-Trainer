

https://github.com/abhamidi-1234/AI-Personal-Trainer/assets/13187234/e97af46a-15fc-42ed-8877-dd4076682720



## Introduction
In recent years, computer vision has become an integral part of various applications, ranging from facial recognition to object detection. One fascinating application of computer vision is in the realm of fitness, where it can be leveraged to create intelligent personal trainers. In this article, we delve into the technical details of a computer vision project that utilizes Google's MediaPipe library for pose detection and OpenCV for building an AI personal trainer capable of counting bicep curls, displaying the pose, and measuring the angle between the arms during each curl.

## Background

**1. MediaPipe Library**
MediaPipe is an open-source library developed by Google that provides a framework for building cross-platform, customizable, and real-time solutions for various tasks such as face detection, hand tracking, and pose estimation. In our project, we focus on the pose estimation module of MediaPipe, which can accurately detect key points on the human body.

**2. OpenCV**
OpenCV (Open Source Computer Vision Library) is a widely used open-source computer vision and machine learning software library. It provides tools for image processing and computer vision algorithms, making it an excellent choice for developing applications that require image and video analysis.

## Project Overview

**1. Pose Detection with MediaPipe**

The first step in our project involves using MediaPipe to detect the pose of a person in a given frame. The pose estimation model in MediaPipe identifies key points such as joints and landmarks on the human body, allowing us to track the movement of specific body parts.

![Img](https://github.com/abhamidi-1234/AI-Personal-Trainer/blob/main/Capture1.PNG)

**2. Bicep Curl Detection**

Once the pose is detected, we focus on identifying the bicep curl exercise. This involves tracking the movement of key points corresponding to the shoulder, elbow, and wrist, and measuring the angle between the user's arms during each bicep curl.

**3. Integration with OpenCV**

Finally, we integrate the bicep curl detection and angle measurement logic with OpenCV to create a real-time feedback system. This involves capturing video frames, running the pose estimation model, and overlaying the relevant information on the video feed.

![Img](https://github.com/abhamidi-1234/AI-Personal-Trainer/blob/main/Capture2.PNG)

## Notes

1. This won't work on Google Colab
2. I also had issues running this with the pyCharm IDE. It worked after I degraded OpenCV version to 4.5.5.62
3. You can also use a webcam for real-time exercise detection and count
4. I have included the logic for only Bicep Curls. You include other exercises as well
5. Credit to CVZone's Murtaza Hassan videos

## How to reach me

https://www.linkedin.com/in/abhishek-bhamidipati/

https://abhishekcmu.wixsite.com/home

https://github.com/abhamidi-1234 (PLEASE STAR MY REPOSITORIES)
