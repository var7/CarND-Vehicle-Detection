# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


In this project, the goal is to write a software pipeline to detect vehicles in a video. For further details check out the [writeup]()

The Project
---
**I have implemented Tiny YOLOv2, a Deep learning based approach that can detect objects in images**  

The (revised) goals / steps of this (Deep Learning) project are the following:

* Implement a Keras model of tiny YOLOv2
* Use pre-trained weights for the model and load them
* Test that the network works for the given test images
* Fine-tune parameters and perform pre-processing of image to prevent false positives
* Run the pipeline on a video stream and estimate a bounding box for vehicles detected.

## YOLOv2

The papers for YOLO can be found at [YOLOv2](https://arxiv.org/abs/1612.08242) and [YOLOv1](https://arxiv.org/abs/1506.02640). 

### Summary of how YOLO works
[yolo]: ./output_images/yolo2.png

YOLO applies a single network to the whole image. The network divides the image into regions and predicts bounding boxes and probabilities of each region. The bounding boxes are weighted by the predicted probabilities. 

![yolo]

## Results
### Video Implementation
The video can be viewed by clicking on the thumbnail below

[![Advanced Lane Finding](https://img.youtube.com/vi/mEdwV9ww3Rw/0.jpg)](https://www.youtube.com/watch?v=mEdwV9ww3Rw)

