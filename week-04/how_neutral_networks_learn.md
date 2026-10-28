# Week 04 How Does a Neural Network Learn?

## 1. Introduction

A neural network learns by comparing predictions with expected results and adjusting its parameters to reduce prediction errors.

The main stages are forward propagation, loss calculation, backpropagation and optimization.

## 2. Training Flow Diagram

```text
Input Training Data
        |
        v
  Forward Propagation
        |
        v
  Generate Prediction
        |
        v
    Calculate Loss
        |
        v
   Backpropagation
        |
        v
 Update Weights and Biases
        |
        v
  Repeat Training Process
        |
        v
 Evaluate Model Performance
```

## 3. Forward Propagation

Input data passes through the network to produce a prediction. Each layer performs calculations using its current weights, biases and activation functions.

## 4. Loss Calculation

A loss function measures the difference between the prediction and the expected target.

Classification models may use cross-entropy loss, while regression models may use mean squared error.

## 5. Backpropagation

Backpropagation calculates gradients that indicate how the trainable parameters affect the loss. It uses the chain rule of calculus to calculate these gradients through the network.

## 6. Optimization

An optimizer uses the gradients to update the weights and biases.

A simplified gradient descent update is:

w_new = w_old − η × (∂L/∂w)

Here, η is the learning rate and ∂L/∂w is the gradient of the loss with respect to the weight.

A learning rate that is too large may make training unstable, while one that is too small may slow learning.

## 7. Epochs and Batches

- **Batch:** A group of training examples processed together.
- **Iteration:** Usually one optimizer update using a batch.
- **Epoch:** One complete pass through the training dataset.

Training commonly involves multiple batches and epochs.

## 8. Training Versus Inference

| Training | Inference |
|---|---|
| Learns from training examples | Makes predictions on new inputs |
| Updates model parameters | Normally keeps parameters fixed |
| Uses loss and gradients | Uses learned parameters to generate outputs |

## 9. Understanding Overfitting

Overfitting occurs when a model performs well on training data but poorly on unseen examples.

Ways to help reduce overfitting include:
- Using representative training data.
- Monitoring validation performance.
- Applying appropriate regularization.
- Avoiding unnecessary model complexity.
- Evaluating on a separate test set.

## 10. Importance of Correct Labels

Incorrect labels can mislead the model during training. For example, a defective wafer image incorrectly labelled as defect-free can encourage the model to learn an incorrect relationship.

## Conclusion

Neural networks learn through repeated predictions, loss calculation, backpropagation and parameter updates. Validation and testing help determine whether the model generalizes to unseen data.

## Sources

1. Google for Developers — [Neural Networks](https://developers.google.com/machine-learning/crash-course/neural-networks)
2. Google for Developers — [Overfitting](https://developers.google.com/machine-learning/crash-course/overfitting)
3. Google for Developers — [Machine Learning Crash Course Exercises](https://developers.google.com/machine-learning/crash-course/exercises)
