# Yolov5 Object Detection with OpenVINO™ Toolkit™

The YOLOv5 algorithm is making big waves in the computer vision and machine learning communities.
It is real-time object detection algorithm that performs image recognition tasks by taking an image as input 
and then predicting bounding boxes and class probabilities for each object in the image.

YOLO stands for “You Only Look Once”, it is a popular family of real-time object detection algorithms. 
The original YOLO object detector was first released in 2016. Since then, different versions and variants of YOLO have been proposed, each providing a significant increase in performance and efficiency.
YOLOv7 is next stage of evalution of YOLO models family which provides a greatly improved real-time object detection accuracy without increasing the inference costs.
More details about its realization can be found in original model [paper](https://arxiv.org/abs/2207.02696) and [repository](https://github.com/WongKinYiu/yolov7)

Real-time object detection is often used as a key component in computer vision systems. 
Applications that use real-time object detection models include video analytics, robotics, autonomous vehicles, multi-object tracking and object counting, medical image analysis, and many others.


This tutorial demonstrates step-by-step instructions on how to run and optimize PyTorch\* Yolo V7 with OpenVINO.

The tutorial consists of the following steps:
- Prepare PyTorch model
- Download and prepare dataset
- Validate original model
- Convert PyTorch model to ONNX
- Convert ONNX model to OpenVINO IR
- Validate converted model
