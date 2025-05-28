# 3d-perceptron-classification
Python implementation of the Perceptron Learning Algorithm to classify 3D points, analyze convergence, and validate linearly separable binary problems.

🧠 3D Perceptron Classification and Convergence Analysis
This project implements the Perceptron Learning Algorithm from scratch in Python to classify 3-dimensional data into two classes. It also includes convergence analysis with varying hyperparameters and checks for linear separability across different class combinations.

📌 Objectives
Classify 3D binary data using the perceptron learning rule.

Determine linearly separable binary problems from multi-class data.

Analyze convergence behavior by tuning learning rate and epochs.

🗂️ Key Features
🔹 1. Perceptron Learning Algorithm
Works on 3D input points.

Step activation function.

Iterative weight updates until convergence or max epochs reached.

🔹 2. Linearly Separable Combinations
Binary class labels created from multi-class dataset.

Validates linearly separable scenarios across class combinations.

🔹 3. Convergence Analysis
Vary learning rate (α) and epoch count.

Observe effects on:

Accuracy

Convergence speed

Final weights and bias

📈 Output Metrics
Accuracy

Final weights and bias

Epochs to converge

Separability status

🧪 Sample Results
Learning Rate	Epochs	Accuracy	Converged
0.01	100	84.5%	Yes
0.1	50	91.0%	Yes
0.5	20	95.0%	No

🧠 Concepts Used
Perceptron Learning Rule

Binary classification

Step activation

Gradient-free optimization

Data transformation for class separation
