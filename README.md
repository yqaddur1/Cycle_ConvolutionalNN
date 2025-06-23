# Cycle Mentorship Program – Convolutional Neural Networks

This repository contains the results of a machine learning mentorship project I led as part of the **Cycle Mentorship Program** at *The Ohio State University*. I had the pleasure of mentoring a talented first-year student on a comparative study of neural networks trained on the **CIFAR-10** image dataset.

## Project Focus

Our study focuses on two key aspects:

- **Architecture**: Comparing networks with and without convolutional layers.
- **Optimizer Choice**: Evaluating the impact of different optimizers on performance.

## Key Findings

- Networks with **convolutional layers** consistently outperform fully connected architectures, regardless of the optimizer used.
- Among the optimizers, **Stochastic Gradient Descent (SGD) with momentum** performed the best overall.

## Additional Insights

We also analyzed the learned filters in the first convolutional layer to better understand the types of features each kernel captures after training. This provided insight into early-stage feature extraction and highlighted the benefits of convolutional architectures in image classification tasks.
