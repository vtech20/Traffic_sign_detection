# Traffic_sign_detection

Detecting & Classifying Over 70 Types of Road Traffic Signs with the Yolo v5 Algorithm. You Only Look Once is referred to as YOLO in an abbreviation. Version 5, which Ultralytics released in June 2020, is now the most sophisticated object detection algorithm on the market. 

It is a cutting-edge convolutional neural network (CNN) that accurately detects objects in real-time. 

This method processes the entire image using a single neural network, then divides it into parts and forecasts bounding boxes and probabilities for each component. 

The predicted probability weighs these bounding boxes.

The main purpose of Model Backbone is to extract important features from an input image. In YOLO v5, CSP(Cross Stage Partial Networks) are utilised as the framework to extract highly beneficial properties from an input image.

In this repo, since we are using the data from a google drive, we used a package gdown to download data from the google drive.

Google Drive URL: https://drive.google.com/file/d/1gQD1OovQDyjMlUEWl6IEn2mzgS6KNppX/view?usp=sharing

we need to provide the id to download the file from google drive link.

Example: !gdown --id 1gQD1OovQDyjMlUEWl6IEn2mzgS6KNppX

