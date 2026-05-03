# L02 Deploying an AI Model on a Simulated Edge Device

## Assignment Summary
This lab provides two pathways for demonstrating understanding of the TensorFlow Lite deployment workflow. Only one option may be selected. The assignment must be submitted as a PDF using the required file naming format. The goal is to understand the complete process of creating, training, converting, and deploying an AI model on a simulated edge device.

## Learning Objectives
This assignment is designed to support the following outcomes:

1. Understand how to conceptually design a full machine learning workflow for edge deployment  
2. Recognize the steps required to install Python, TensorFlow, TensorFlow Lite, and Jupyter Notebook  
3. Understand how a neural network is structured, trained, evaluated, and saved  
4. Learn how TensorFlow Lite converts a trained model into an optimized format for resource constrained devices  
5. Understand how inference is performed using the TensorFlow Lite Interpreter  
6. Reflect on challenges, insights, and real world applications of the workflow  

The uploaded conceptual report demonstrates this workflow clearly. One excerpt notes that the goal was to practice the “end to end workflow for moving a trained model from development into a lightweight format suitable for deployment on devices with limited resources.”  
The reflective journal emphasizes that TensorFlow Lite is designed for “real world deployments where compute, memory, and power are constrained.”

## Assignment Requirements

### Option A Conceptual Approach
Only one option may be selected. The conceptual option requires documenting the entire workflow on paper without running code.

### Part 1 Conceptual Setup of the Development Environment
The assignment requires researching and documenting:

1. Python installation steps including downloading from the official website and configuring PATH  
2. TensorFlow and TensorFlow Lite installation using a package manager  
3. Jupyter Notebook installation and launch steps  

The uploaded report includes examples of verified installations. One excerpt shows confirmation of TensorFlow installation:  
“Requirement already satisfied: tensorflow 2.15.1”

### Part 2 Conceptual Creation and Training of an AI Model
The assignment requires documenting:

1. A conceptual neural network architecture for MNIST  
2. Data loading and preprocessing including normalization  
3. Model compilation steps including optimizer, loss function, and metrics  
4. Training steps including number of epochs  

The uploaded report demonstrates this process. One excerpt shows training logs with accuracy values such as “val accuracy 0.9162.”

### Part 3 Conceptual Conversion and Saving of the Model
The assignment requires explaining:

1. The purpose of converting a trained model to TensorFlow Lite  
2. The steps involved in using the TensorFlow Lite converter  
3. How to save the converted model  

The uploaded report includes a conversion confirmation:  
“Model successfully converted and saved as mnist_model.tflite”

### Part 4 Conceptual Deployment of the Model
The assignment requires documenting:

1. How to load a TensorFlow Lite model using the interpreter  
2. How to allocate tensors and inspect input and output shapes  
3. How to test the model on a sample input  

The uploaded report includes interpreter details such as:  
“Input shape array [1, 28, 28] and output shape array [1, 10]”

### Reflective Journal Requirements
The assignment requires a one to two page reflection including:

1. Challenges faced  
2. Learning outcomes  
3. Real world applications  

The uploaded reflective journal highlights challenges with environment stability and version alignment. It also explains that validation after conversion is essential because “a model that trains correctly is not automatically ready for deployment until inference is tested in the target runtime.”

## Key Learning Points from the Uploaded Work
The uploaded documents demonstrate several important insights:

1. Environment consistency is critical for TensorFlow Lite conversion  
2. Normalization improves training stability  
3. TensorFlow Lite is optimized for edge devices with limited resources  
4. Interpreter validation confirms that the converted model behaves correctly  
5. Documentation of each step ensures reproducibility  
6. The workflow mirrors real world edge AI deployment practices  

## Submission Requirements
The assignment must be submitted as a PDF using the required naming format:  
L02_LastName_FirstName_ITAI3377

Only one option may be selected. The document must clearly indicate the chosen approach.

## Evaluation Criteria
The assignment is graded on:

Accuracy of documented steps  
Completeness of all required parts  
Clarity of explanations  
Demonstrated understanding through the conceptual design and reflective journal

