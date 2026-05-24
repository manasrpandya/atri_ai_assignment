Hey there! this is Manas Pandya's submission for the assignment at Atri AI (internship selection process)

In this assignment, I have been tasked with implementing a NN from scratch to work on Fashion MNIST data. For this, I have created a single ipynb file (shown in the repo as 'atri_assignment.ipynb'). 

To the evaluators, a small note, I had worked on this without really paying note to the last point in the assignment; and thus have had only a single commit. Hope that doesn't affect my selection.

# Notebook Structure

### Question 1: Fashion-MNIST Dataset
- Loads dataset and visualizes 1 sample per class
- Shows data shapes and preprocessing

### Question 2: Feedforward Neural Network
- Network architecture is kept flexible as directed (can add/remove layers)
- Supports activation functions: ReLU, Sigmoid, Tanh
- Weight initialization: Random/Xavier
- Forward pass with softmax o/p layer

### Question 3: Backpropagation with Optimizers
Implements 6 optimizers:
1. **SGD** - Basic stochastic gradient descent
2. **Momentum** - Momentum-based gradient descent
3. **Nesterov** - Nesterov accelerated gradient
4. **RMSprop** - Root mean square propagation
5. **Adam** - Adaptive moment estimation
6. **Nadam** - Nesterov + Adam

Includes `Trainer` class for training loop with:
- Batch processing
- Gradient computation via backprop
- Weight decay/L2 regularization
- Both cross-entropy and squared error loss

### Question 4-5: Wandb Hyperparameter Sweep
- Bayes search over 9 hyperparameters
- Evaluates 2^9 possible combinations efficiently
- Logs all metrics to Wandb dashboard

### Question 6: Analysis
- Parallel coordinates plot interpretation
- Correlation analysis
- Recommendations for best hyperparameters

### Question 7: Best Model Evaluation
- Confusion matrix visualization
- Per-class accuracy breakdown
- Test set evaluation

### Question 8: Loss Function Comparison
- Cross-Entropy vs Squared Error
- Comparison plots and analysis
- Why cross-entropy is better for classification

### Question 10: Transfer Learning to MNIST
- Takes learnings from Fashion-MNIST
- Tests 3 recommended configurations on MNIST
- Shows generalization across datasets

  Thank you! for considering my application, hope to work with your team.
