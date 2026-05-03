# Module 4  
Conceptual Design of an IIoT Sensor Network and Protocol Experimentation  
and  
A04 Individual Reflective Journal

## Overview
Module 4 focuses on the conceptual design and simulation of an Industrial Internet of Things sensor network. The lab explores three major communication protocols used in industrial environments: MQTT, CoAP, and OPC UA. The module also includes an individual reflective journal that documents insights, challenges, and future applications of the project. Together these activities build practical understanding of IIoT communication, data generation, real time visualization, and protocol behavior.

---

# Part One  
Lab 04 Conceptual Design of an IIoT Sensor Network  
Individual Lab Assignment

## Objective
The goal of this lab is to design and simulate an IIoT sensor network that generates temperature and humidity data, transmits it using MQTT, CoAP, and OPC UA, and visualizes the results in real time. The lab emphasizes protocol behavior, data flow, virtual environments, and GitHub workflows.

## Learning Outcomes
This lab supports the following outcomes:

1. Understand how MQTT, CoAP, and OPC UA differ in architecture, performance, and use cases  
2. Learn how to simulate sensor data using Python  
3. Gain experience with asynchronous programming and protocol specific client libraries  
4. Visualize real time data using Pandas and Matplotlib  
5. Strengthen skills in virtual environments and GitHub repository management  
6. Build a conceptual foundation for industrial communication systems  

Insights from the uploaded reflective journal reinforce these outcomes.  
One excerpt notes that MQTT is “lightweight, fast, and ideal for continuous sensor updates,” while CoAP mirrors HTTP concepts in a form optimized for constrained devices. Another excerpt highlights that OPC UA provides “structured, secure, and highly interoperable design,” making it suitable for manufacturing environments.

---

## Lab Requirements

### Step 1 Development Environment Setup
The lab requires creating a project directory, activating a Python virtual environment, and preparing the workspace for simulation.

### Step 2 Install Required Libraries
The following Python packages must be installed:

pandas  
numpy  
paho mqtt  
aiocoap  
asyncua  
matplotlib  

Mosquitto must also be installed to serve as the MQTT broker.

### Step 3 Sensor Data Simulation
Three scripts must be created:

mqtt_sensor_simulation.py  
coap_sensor_simulation.py  
opcua_sensor_simulation.py  

Each script generates random temperature and humidity values every second and transmits them using the appropriate protocol.

### Step 4 Data Visualization
A visualization script must be created to subscribe to MQTT data and plot temperature and humidity in real time. Similar scripts may be created for CoAP and OPC UA if needed.

### Step 5 Running the Simulation
The MQTT broker must be started, followed by running each simulation script in separate terminals. The visualization script is then executed to display real time graphs.

### Step 6 GitHub Submission
The project must be organized into a structured directory and uploaded to GitHub using GitHub Desktop.  
A README.md must be included with setup instructions and project details.

### File Naming Format
L04_SubmitterName_GroupName_ITAI_3377

---

# Part Two  
A04 Individual Reflective Journal  
IIoT Protocols Project

## Required Journal Sections

### Introduction
A brief overview of the project, including goals and expectations.  
The uploaded journal describes the objective as understanding how MQTT, CoAP, and OPC UA differ in architecture and performance while strengthening Python scripting and real time visualization skills.

### Personal Contributions
A description of specific tasks completed.  
The uploaded journal lists contributions such as implementing all three simulation scripts and developing the visualization logic.

### Learning Outcomes
A detailed explanation of what was learned about each protocol.  
The journal highlights that MQTT excels in speed, CoAP is efficient for constrained devices, and OPC UA provides robust data modeling.

### Challenges and Solutions
A description of issues encountered and how they were resolved.  
Examples from the journal include event loop conflicts in CoAP, port binding issues in OPC UA, and visualization flickering.

### Future Applications
A discussion of how the knowledge can be applied in future IIoT or professional scenarios.  
The journal suggests expanding sensor types, creating unified dashboards, adding analytics, and integrating cloud platforms.

### File Naming Format
A04_YourName_ITAI_3377

---

# Summary
Module 4 provides a comprehensive introduction to IIoT communication protocols and real time data simulation. The lab builds practical skills in Python, asynchronous programming, protocol configuration, and visualization. The reflective journal reinforces conceptual understanding by documenting insights, challenges, and future applications. Together these assignments create a strong foundation for designing scalable and interoperable IIoT systems.

