# Automatic Number Plate Recognition
![my badge](https://img.shields.io/badge/Python-3-blue)
![my badge](https://img.shields.io/badge/Deep-Learning-brightgreen)
![my badge](https://img.shields.io/badge/Flask-App-green)
![my badge](https://img.shields.io/badge/Object-Detection-yellowgreen)
![my badge](https://img.shields.io/badge/YOLO-v5-orange)
![my badge](https://img.shields.io/badge/Paddle-OCR-purple)
![my badge](https://img.shields.io/badge/-GIT-green)

# About The Project

This project has been developed to detect and recognize a number plate in an image containing a vehicle

# Project Description 

A web app has been developed for this project which takes a image as an input and returns the predictions as a result. The object detection model trained for the project is YOLOv5.For the OCR (Optical Character Recognition) part of the project, PaddleOCR is used. The input image is first encoded to base64 format after which is it send to the backend where the image is decoded and then sent to Yolov5 for license plate detection. Then the image of the detected license plate is sent to Paddle OCR for character Recognition.

# Dataset Used

This dataset is taken from LearnOpenCv website.

Dataset : [Link](https://learnopencv.com/automatic-license-plate-recognition-using-deep-learning#Detection-of-License-plate-using-YOLOv4)

# Project Structure


<img width="229" alt="image" src="https://user-images.githubusercontent.com/58848985/169958144-712f2c5f-a765-493a-a075-092098f40b6a.png">


* com_in_ineuron_ai_utils - This directory contains the script for all necessary function
* my_model - This directory contains trained object detection model used for prediction
* templates - This directory contains the frontend files for the webapp
* Sample_images - This directory contains sample images to test the app

# Preview of the Web App

Web App Main Page :

<img width="960" alt="image" src="https://user-images.githubusercontent.com/58848985/161687024-ed21efcd-a887-45c7-8d72-5b3f3cdc1bd6.png">

After Prediction: 

<img width="960" alt="image" src="https://user-images.githubusercontent.com/58848985/161687308-577f42c0-7ee8-4ff9-b876-d34a7907a518.png">


