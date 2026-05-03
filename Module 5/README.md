 # Module 5
AIoT Data Acquisition and Preprocessing

## Overview
Module 5 introduces the core concepts of data acquisition and preprocessing within AIoT systems. The module focuses on how data is collected, cleaned, transformed, and prepared for analysis in environments where edge devices and IoT sensors generate continuous information streams. These concepts form the foundation for building reliable and efficient AIoT pipelines.

---

## Learning Objectives
This module supports the following learning outcomes:

1. Understand the differences between batch and real time data collection  
2. Learn how sampling rates influence system performance and resource usage  
3. Recognize the importance of data cleaning and preprocessing in AIoT workflows  
4. Explore filtering, aggregation, and feature extraction techniques  
5. Understand how data transformation prepares information for AI models  
6. Compare storage options for edge and cloud environments  
7. Identify trade offs involving latency, storage capacity, connectivity, and security  
8. Distinguish between traditional AI and AIoT processing approaches  

---

## Key Concepts from the Module

### Data Collection Strategies
The module explains two primary strategies:

Batch collection  
Data is gathered over time and processed in bulk.  
Useful for non critical applications such as inventory management or financial reporting.

Real time collection  
Data is captured and processed immediately.  
Essential for applications such as traffic management, sensor networks, and health monitoring.

### Data Sampling Rates
Sampling rate determines how frequently data points are collected.  
Higher sampling rates provide more detail but require more resources.  
Lower sampling rates reduce resource usage but may lose important information.  
The goal is to balance granularity with system constraints.

---

## Data Preprocessing Techniques

### Filtering
Filtering removes noise and unwanted signals.  
The module highlights three types:

Low pass filtering  
High pass filtering  
Band pass filtering  

These techniques refine sensor data to improve clarity and model performance.

### Aggregation
Aggregation summarizes data for efficiency.  
Common methods include averaging, summation, and identifying maximum or minimum values.  
Aggregation reduces storage needs and speeds up analysis.

### Feature Extraction
Feature extraction transforms raw sensor data into meaningful inputs for AI models.  
Examples include:

Statistical features such as mean and variance  
Time domain features such as peaks and zero crossings  
Frequency domain features using FFT  

---

## Data Cleaning
Data cleaning ensures accuracy and consistency.  
The module covers:

Handling missing values  
Noise reduction  
Normalization  
Outlier detection  

Clean data improves the reliability of AIoT systems.

---

## Data Transformation
Data transformation prepares information for analysis.  
Key techniques include:

Normalization  
Scaling  
Encoding categorical values  

These steps ensure compatibility with machine learning models.

---

## Data Storage Options

### Local Edge Storage
Advantages  
Reduced latency  
Lower dependency on connectivity  
Improved privacy  

Disadvantages  
Limited capacity  
Higher management requirements  

### Cloud Storage
Advantages  
Scalability  
Large capacity  
Advanced management tools  

Disadvantages  
Connectivity dependency  
Potential latency  
Privacy considerations  

---

## Considerations and Trade Offs
The module emphasizes evaluating:

Latency versus storage capacity  
Connectivity requirements  
Security and privacy needs  

These factors influence how AIoT systems are designed and deployed.

---

## Traditional AI vs AIoT
Traditional AI relies on centralized cloud processing and large computational resources.  
AIoT distributes processing across edge devices, enabling real time decision making and reducing bandwidth usage.

---

## Edge Devices vs Traditional IoT Devices
Edge devices perform local processing and analytics, reducing latency and enabling immediate responses.  
Traditional IoT devices primarily collect data and send it to the cloud for processing.

---

## Assignments
There are no assignments or labs for Module 5.  
This module serves as a conceptual foundation for upcoming work involving data pipelines and AIoT system design.

