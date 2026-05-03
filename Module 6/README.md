# Module 6 
AI Driven Data Analytics with Nixtla  
IIoT Time Series Forecasting Lab and Presentation

## Overview
Module 6 introduces time series forecasting for Industrial Internet of Things data. The module focuses on data preparation, model selection, feature engineering, evaluation, and generative modeling using Nixtla or Wolfram tools. The work is divided into two connected assignments.  
L06 is the technical lab where forecasting models are implemented and evaluated.  
A06 is the presentation summarizing findings and recommendations from the lab.

---

# Part One  
L06 IIoT Time Series Forecasting Lab  
Individual or Group Assignment

## Objective
The goal of this lab is to apply forecasting techniques to real world IIoT temperature data. The lab includes data preprocessing, model training, feature engineering, evaluation, and the use of generative models to enhance the dataset.

## Learning Outcomes
This lab supports the following outcomes:

1. Understand how to prepare time series data for forecasting  
2. Learn how to select and train forecasting models using Nixtla or Wolfram  
3. Apply automated and custom feature engineering techniques  
4. Evaluate forecasting models using appropriate metrics  
5. Perform rolling origin cross validation for robustness  
6. Use generative models to create synthetic time series data  
7. Analyze how synthetic data affects model performance  
8. Document the full forecasting workflow in a structured report  

---

## Lab Requirements

### 1 Data Preparation
Download the IoT Temperature Forecasting dataset from Kaggle.  
Inspect the dataset for missing values, outliers, and normalization needs.  
Split the data into training and testing sets.

### 2 Model Selection and Training
Two options are available:

Nixtla AutoML  
Use Nixtla tools to automatically select and train a forecasting model.  
Document the selection process and justify the chosen model.

Wolfram Language  
Use TimeSeriesModelFit, FindMachineLearningModel, or Predict.  
Document the reasoning behind the chosen method.  
Submit Wolfram notebooks or scripts if this option is selected.

### 3 Feature Engineering
Use automated feature extraction tools.  
Create at least two custom features based on IIoT domain knowledge.  
Explain the significance of each feature.

### 4 Evaluation
Evaluate the model using metrics such as MAE, MSE, and MASE.  
Perform rolling origin cross validation.  
Summarize results and discuss improvements.

### 5 Generative Modeling
Use a Variational Autoencoder to generate synthetic time series data.  
Augment the training set with synthetic samples.  
Retrain the model and evaluate performance changes.

### 6 Final Report Requirements
The report must include:

Data preparation steps  
Model selection and training process  
Feature engineering and custom feature explanations  
Evaluation results and cross validation  
Generative modeling and its impact  
Individual reflection for each team member if working in a group  
References  

### Submission Format
Submit the report as a PDF.  
Include Jupyter notebooks or scripts.  
File naming format:  
L06_GroupName_SubmitterName_ITAI3377.pdf  
or  
L06_SubmitterName_ITAI3377.pdf  

---

# Part Two  
A06 IIoT Forecasting Presentation  
Individual or Group Assignment

## Objective
The goal of this presentation is to summarize the findings from the L06 lab and communicate insights, results, and recommendations in a clear and concise format.

## Presentation Requirements

### Slide Content
The presentation should include:

Introduction  
Overview of the dataset and forecasting problem.

Data Preparation  
Summary of preprocessing steps.

Model Selection and Training  
Justification of the chosen model and tools.

Feature Engineering and Evaluation  
Key features, performance metrics, and evaluation results.

Generative Models  
Impact of synthetic data on forecasting accuracy.

Key Insights and Recommendations  
Summary of findings and practical takeaways.

### Video Recording
Record a narrated presentation.  
Each group member must contribute if working in a group.  
Audio and video must be clear and professional.

### Submission Format
Submit the video file.  
File naming format:  
A06_GroupName_SubmitterName_ITAI3377.mp4  
or  
A06_SubmitterName_ITAI3377.mp4  

---

# Summary
Module 6 provides hands on experience with time series forecasting for IIoT systems. The lab builds technical skills in data preparation, model training, feature engineering, evaluation, and generative modeling. The presentation reinforces communication skills by summarizing insights and recommendations. Together these assignments develop a strong foundation for AI driven analytics in industrial environments.

