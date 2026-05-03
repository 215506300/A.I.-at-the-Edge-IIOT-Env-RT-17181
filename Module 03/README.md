# Module 3 README  
Deploying a Simple AI Model on a Simulated Edge Device  
and  
Case Study Analysis on Edge Computing Video Analytics

## Overview
Module 3 focuses on two major components.  
The first is a hands on lab involving deployment of a simple AI model on a simulated edge device using Visual Studio Code.  
The second is an individual case study analysis examining edge computing video analytics in a smart city environment.  
Together these activities build practical and analytical skills related to edge AI workflows, model deployment, and real world applications of intelligent sensing systems.

---

# Part One  
L03 Deploying a Simple AI Model on a Simulated Edge Device  
Individual Lab Assignment

## Objective
The goal of this lab is to deploy a simple AI model on a simulated edge device in order to understand the fundamentals of edge computing, model optimization, and AI integration within constrained environments.

## Learning Outcomes
This lab supports the following learning outcomes:

1. Understand how to configure a development environment in Visual Studio Code  
2. Learn how to load, preprocess, and structure datasets for edge deployment  
3. Train a lightweight convolutional neural network suitable for embedded inference  
4. Convert a trained model to TensorFlow Lite format for resource constrained devices  
5. Upload and test the model using Edge Impulse’s simulated device environment  
6. Document accuracy, latency, and inference behavior  
7. Reflect on the deployment workflow and challenges  

Insights from previous work reinforce these outcomes.  
The uploaded L02 simulation documentation notes that TensorFlow Lite conversion produces a model that is “significantly smaller” while maintaining accuracy, and the reflective journal emphasizes that simulated devices help make deployment “tangible rather than theoretical.”

---

## Lab Requirements

### Step 1 Environment Setup
The lab requires installation of the following tools:

Python  
Visual Studio Code  
TensorFlow using pip  
Node.js and npm  
Edge Impulse CLI using npm  

### Step 2 Dataset Preparation
The MNIST dataset must be loaded and normalized.  
Images are reshaped to match the expected input format for a convolutional neural network.

### Step 3 Model Training
A simple CNN is implemented with:

Conv2D  
MaxPooling2D  
Flatten  
Dense layers  

The model is compiled with Adam, sparse categorical cross entropy, and accuracy metrics.  
Training runs for five epochs with validation on the test set.

### Step 4 Model Conversion and Deployment
The trained model is converted to TensorFlow Lite using the TFLiteConverter API.  
The resulting file is uploaded to Edge Impulse using the CLI.  
The simulated device environment is used to test inference behavior.

### Step 5 Testing and Validation
Inference is run on sample inputs.  
Accuracy, latency, and output confidence scores are recorded.  
Screenshots and logs are included in the documentation.

### Deliverables
Simulation documentation including screenshots  
Reflective journal describing observations, challenges, and insights  
File naming format: L03_Student_Name_ITAI3377

---

# Part Two  
A03 Case Study Analysis  
Edge Computing Video Analytics for Real Time Traffic Monitoring in a Smart City  
Individual Assignment

## Objective
The goal of this assignment is to analyze and critically evaluate the Liverpool Smart Pedestrians project, focusing on its methodology, technology stack, validation results, real world applications, and future potential.

## Learning Outcomes
This assignment supports the following outcomes:

1. Understand how edge computing enables privacy preserving video analytics  
2. Analyze the design of an edge AI sensor using hardware such as the NVIDIA Jetson TX2  
3. Evaluate object detection and tracking algorithms such as YOLO V3 and SORT  
4. Connect case study findings to concepts from Modules 2 and 3  
5. Identify challenges and propose improvements based on current technological advancements  
6. Develop critical thinking skills through structured analysis and personal evaluation  

The uploaded A03 report demonstrates these outcomes clearly.  
One excerpt notes that the project “transformed the existing CCTV network into an intelligent sensing infrastructure,” while another highlights that the Jetson TX2 provided “GPU accelerated performance and low power consumption.”

---

## Assignment Requirements

### A Introduction and Objectives
Summarize the goals of the Liverpool Smart Pedestrians project and the urban planning challenges it addresses.

### B Methodology
Describe the methodology including community engagement, sensor requirements, and constraints such as privacy laws and bandwidth limitations.

### C Technology and Implementation
Analyze the hardware and software stack including:

NVIDIA Jetson TX2  
YOLO V3  
SORT tracking  
Edge computing principles  

### D Validation and Performance
Evaluate accuracy, speed, GPU utilization, and tracking stability.

### E Real World Applications
Discuss indoor emergency evacuation testing and outdoor deployment across Liverpool.  
Connect these applications to Module 3 concepts such as sensor networks and edge gateways.

### F Challenges and Future Work
Identify limitations such as occlusion, lighting, and bandwidth.  
Discuss improvements and modern technologies including YOLOv7, transformer based vision models, Jetson Orin, 5G, and modern IoT protocols.

### G Personal Evaluation
Provide a critical evaluation of the project’s success, impact, and potential enhancements.

### Submission Requirements
Minimum 200 words plus references  
APA format  
File naming format: A03_YourName_ITAI_3377  

---

# Summary
Module 3 combines practical deployment skills with analytical evaluation of real world edge AI systems.  
The lab builds technical confidence in model training, conversion, and simulated deployment.  
The case study analysis strengthens understanding of edge architectures, sensor design, and smart city applications.  
Together these assignments reinforce the importance of efficiency, privacy, scalability, and reliability in modern edge AI solutions.

