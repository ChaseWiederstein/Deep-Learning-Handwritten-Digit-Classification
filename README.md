# Deep-Learning-Handwritten-Digit-Classification

## Executive Summary
This project delves into the application and optimization of various deep learning models, including Multilayer Perceptrons (MLP), Convolutional Neural Networks (CNN), and Locally Connected Neural Networks (LCNN), targeting the recognition of handwritten digits sourced from U.S. Postal Service envelopes. The primary objective is to enhance model accuracy through systematic hyperparameter tuning, showcasing significant variations in model performance and highlighting the crucial role of strategic hyperparameter adjustments.

## Key Sections
1. **The Dataset**: Utilizes normalized 16x16 grayscale images of handwritten digits, aiming for accurate digit class assignment within a 10-class system (digits 0-9). Special thanks are attributed to Yann LeCun and AT&T Research Labs for dataset provision.
2. **Model Architectures**: Describes the implementation of three distinct neural network architectures (MLP, CNN, LCNN) tailored to the project's needs, each adhering to specific design criteria to optimize learning and recognition performance.
3. **Training and Optimization**: Discusses the methodologies employed in training the models using stochastic gradient descent with momentum and cross-entropy loss. It covers the stages from coarse random search to fine-tuned Bayesian optimization, focusing on learning rates, batch sizes, momentum, and dropout rates.
4. **Hyperparameter Impact Analysis**: Details the experimental analysis of how different hyperparameters influence training dynamics and model performance, with visualizations and data highlighting key findings.

## Project Files
- [digitClassification.pdf](digitClassification.pdf): Provides detailed explanations of the MLP, CNN, and LCNN architectures, including design rationales and optimization strategies used in the project.

- [digitClassCode.ipynb](digitClassCode.ipynb): Contains code that implements and visualizes the training and optimization of the models, highlighting the effects of different hyperparameters.






