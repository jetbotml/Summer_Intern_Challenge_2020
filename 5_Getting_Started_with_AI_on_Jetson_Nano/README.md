# Getting Started with AI on Jetson Nano

## Learning Objectives
The power of AI is now in the hands of makers, self-taught developers, and embedded technology enthusiasts everywhere with the NVIDIA Jetson Nano Developer Kit. This easy-to-use, powerful computer lets you run multiple neural networks in parallel for applications like image classification, object detection, segmentation, and speech processing. In this course, you'll use Jupyter iPython notebooks on your own Jetson Nano to build a deep learning classification project with computer vision models.

### Duration 8 hours

### You'll learn how to:
* Set up your Jetson Nano and camera
* Collect image data for classification models
* Annotate image data for regression models
* Train a neural network on your data to create your own models
* Run inference on the Jetson Nano with the models you create
* Upon completion, you'll be able to create your own deep learning classification and regression models with the Jetson Nano.

### Course Details
* Prerequisites: Basic familiarity with Python (helpful, not required)
* Tools, libraries, frameworks used: PyTorch, Jetson Nano
* Assessment Type: Multiple-choice

### Required Hardware 
* NVIDIA Jetson Nano Developer Kit https://www.sparkfun.com/products/16308
  * High-performance microSD card: 32GB minimum (we've tested and recommend this one)
  * 5V 4A power supply with 2.1mm DC barrel connector (we've tested and recommend this one)
  * 2-pin jumper: must be added to the Jetson Nano Developer Kit board to enable power from the barrel jack power supply (here’s an example)
  * Logitech C270 USB Webcam (we've tested and recommend this one).
* Edimax 2-in-1 WiFi and Bluetooth 4.0 Adapter https://www.sparkfun.com/products/15449
  * [Edimax Setup](https://github.com/jetbotml/Summer_Intern_Challange_2020/blob/master/Getting_Started_with_AI_on_Jetson_Nano/wifi_setup) 

### Additional Computer Requirements
A computer with an internet connection and the ability to flash your microSD card

## Steps: Follow the list below as you work through the course. There are some modifications.
### 0. AI Adventures - Google Cloud: https://www.youtube.com/playlist?list=PLIivdWyY5sqJxnwJhe3etaK7utrBiPBQ2
The two listed below will give you a good overview before you start the Nvidia course. 
- What is Machine Learning? 
- Jupyter Tips and Tricks

### Course: https://courses.nvidia.com/courses/course-v1:DLI+C-RX-02+V1/about

### 1. Setting Up Your Jetson Nano: Step-by-step guide to set up your hardware and software for the course projects
1. (Done) Introduction and Download
1. (Done) Prepare for Setup
1. (Done) Write Image to the MicroSD Card
1. (Modified) Setup and First Boot -  We will use the WiFi adapter rather than running in headless mode. 
1. Camera Setup - use Logitech C270 Webcam
1. Hello Camera
1. JupyterLab

### 2. Image Classification
AI and Deep Learning: A brief overview of Deep Learning and how it relates to Artificial Intelligence (AI)
1. Convolutional Neural Networks (CNNs): An introduction to the dominant class of artificial neural networks for computer vision tasks
1. ResNet-18: Specifics on the ResNet-18 network architecture used in the class projects
1. Thumbs Project: Work with the Interactive Classification notebook to create your first project
1. Emotions Project: Build a new project with the same Interactive notebook to detect emotions from facial expressions

### 3. Image Regression
Instructions to create projects that can localize and track image features in a live camera image
1. Classification vs. Regression: With a few changes, your the Classification model can be converted to a Regression model
1. Face XY Project: Build a project that finds the coordinates of facial features
