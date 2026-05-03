# Module 7
IIoT Network Analysis  
Age of Information and Reliability Trade Offs

## Overview
Module 7 introduces the concepts of Age of Information and reliability within Industrial Internet of Things networks. The module focuses on understanding how data freshness and packet loss probability interact, how network parameters influence these metrics, and how machine learning can be used to analyze and predict system behavior. The assignment includes conceptual explanations, data exploration, model development, and analytical insights.

---

# Part One  
Conceptual Understanding

## Objective
The goal of this section is to build a clear understanding of Age of Information, packet loss probability, and traffic types in IIoT systems. These concepts form the foundation for analyzing the dataset and interpreting model results.

## Learning Outcomes
This section supports the following outcomes:

1. Understand the meaning and importance of Age of Information  
2. Recognize the difference between AoI oriented and deadline oriented traffic  
3. Connect theoretical concepts from the assigned research paper to practical analysis  

The required reading explains how AoI measures data freshness and why it is critical for time sensitive IIoT applications. The paper also highlights the trade off between AoI and reliability, which guides the analysis in later steps.

---

# Part Two  
Data Exploration and Visualization

## Objective
The goal of this section is to explore the dataset, understand its structure, and identify patterns that influence AoI and packet loss probability.

## Requirements
Load the dataset using pandas.  
Inspect the first rows, data types, and summary statistics.  
Create at least three visualizations such as:

Scatter plot of transmission probability versus Age of Information  
Box plot of Age of Information grouped by traffic type  
Heatmap of correlations between numerical variables  

## Learning Outcomes
This section supports the following outcomes:

1. Identify relationships between network parameters and AoI  
2. Recognize trends that influence packet loss probability  
3. Develop insights that guide model development  

---

# Part Three  
Machine Learning Model Development

## Objective
The goal of this section is to build a predictive model for Age of Information using a Random Forest regressor.

## Requirements

### Data Preparation
Select relevant features.  
Split into training and testing sets.  
Scale features using StandardScaler.

### Model Training
Train a RandomForestRegressor.  
Generate predictions.  
Evaluate using Mean Squared Error and R squared.

### Model Interpretation
Discuss model performance.  
Analyze feature importance.  
Use the model to predict AoI for three hypothetical network configurations.

## Learning Outcomes
This section supports the following outcomes:

1. Understand how machine learning can model AoI behavior  
2. Identify which network parameters most strongly influence AoI  
3. Evaluate model accuracy and interpret predictive results  

---

# Part Four  
Analysis and Insights

## Objective
The goal of this section is to interpret the results from the data exploration and machine learning model.

## Requirements
Discuss key factors influencing the AoI and packet loss probability trade off.  
Propose strategies for optimizing network performance.  
Describe real world applications where understanding this trade off improves system reliability and data freshness.

## Learning Outcomes
This section supports the following outcomes:

1. Connect model results to IIoT network behavior  
2. Propose practical strategies for improving network performance  
3. Apply insights to real world IIoT scenarios  

---

# Bonus Challenge  
Deep Learning Model

## Objective
The goal of this optional section is to build a neural network that predicts both AoI and packet loss probability.

## Requirements
Create a TensorFlow model with at least one hidden layer.  
Train the model to predict both outputs.  
Evaluate performance.  
Compare results with the Random Forest model.

---

# Assignment Deliverables

## Notebook Submission
Submit a Jupyter Notebook or PDF containing:

All code  
All visualizations  
All analysis  
Clear documentation and comments  

File naming format:  
L07_Notebook_Your_Name_ITAI3377  
or  
L07_Notebook_Submitter_Name_Group_Name_ITAI3377  

## Summary Report
Submit a three page PDF summarizing insights and results.  
File naming format:  
L07_Report_Your_Name_ITAI3377  
or  
L07_Report_Submitter_Name_Group_Name_ITAI3377  

---

# Summary
Module 7 provides a comprehensive introduction to Age of Information and reliability trade offs in IIoT networks. The assignment combines conceptual understanding, data exploration, machine learning, and analytical reasoning. Together these components build a strong foundation for evaluating network performance and designing systems that balance data freshness with reliability.

