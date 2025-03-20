# Deep-Learning-Handwritten-Digit-Classification
## Executive Summary
This project delves into the application and optimization of various deep learning models, including Multilayer Perceptrons (MLP), Convolutional Neural Networks (CNN), and Locally Connected Neural Networks (LCNN), targeting the recognition of handwritten digits sourced from U.S. Postal Service envelopes. The primary objective is to enhance model accuracy through systematic hyperparameter tuning, showcasing significant variations in model performance and highlighting the crucial role of strategic hyperparameter adjustments.

## Key Sections
- **The Dataset**: Utilizes normalized 16x16 grayscale images of handwritten digits, aiming for accurate digit class assignment within a 10-class system (digits 0-9). Special thanks are attributed to Yann LeCun and AT&T Research Labs for dataset provision.
- **Model Architectures**: Describes the implementation of three distinct neural network architectures (MLP, CNN, LCNN) tailored to the project's needs, each adhering to specific design criteria to optimize learning and recognition performance.
- **Training and Optimization**: Discusses the methodologies employed in training the models using stochastic gradient descent with momentum and cross-entropy loss. It covers the stages from coarse random search to fine-tuned Bayesian optimization, focusing on learning rates, batch sizes, momentum, and dropout rates.

## Project Files
- `digitClassification.pdf`: Detailed descriptions and configurations of the MLP, CNN, and LCNN used.
- `digitClassCode.ipynb`: Contains graphical and tabular representations of training progress and outcomes.



