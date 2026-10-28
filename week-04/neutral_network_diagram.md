# week 04 Open the Neural Network

## 1. Introduction

An artificial neural network is a computational model made up of interconnected units called neurons. The neurons are arranged in layers that process numerical data and generate predictions.

During training, the network adjusts its weights and biases to learn useful patterns.

## 2. Neural Network Diagram

```text
        INPUT LAYER
      (Input Features)
        o   o   o
         \  |  /
          \ | /
           \|/
       HIDDEN LAYER
        o   o   o
       / \  |  / \
      /   \ | /   \
       OUTPUT LAYER
          o   o
      (Class Scores)
```

This is a simplified illustration. Real neural networks may contain many more neurons and layers.

## 3. Main Components

### Input Layer

Receives numerical input data. For an image classifier, the inputs may be pixel values.

### Hidden Layers

Process input data and learn useful patterns. A network may contain one or several hidden layers.

### Output Layer

Produces the final result. In a classification task, it may generate scores or probabilities for different categories.

### Weights

Weights determine how strongly one neuron influences another. They are adjusted during training.

### Biases

Biases are trainable values that help adjust the calculations performed by neurons.

### Activation Functions

Activation functions transform neuron outputs and introduce non-linearity. Examples include ReLU, sigmoid and tanh.

## 4. Mathematical Representation of a Neuron

A neuron can calculate a weighted sum of its inputs and a bias:

z = w₁x₁ + w₂x₂ + b

The activation function is then applied:

a = f(z)

Where:

- x represents input values.
- w represents weights.
- b represents the bias.
- f represents the activation function.
- a represents the neuron's output.

## 5. Example: Wafer Image Classification

1. A wafer image is converted into numerical pixel values.
2. The input layer receives the values.
3. Hidden layers process the data and learn visual patterns.
4. The output layer produces scores for possible defect categories.
5. The predicted category is evaluated against known labels.

## 6. Why Training Is Necessary

A newly initialized network does not automatically know how to recognize defects. Training adjusts the weights and biases using examples and their expected outputs.

Poor-quality data or incorrect labels can lead to unreliable predictions.

## Conclusion

Neural networks process numerical data through interconnected layers. Weights, biases and activation functions help the network learn patterns and generate predictions.

## Sources

1. Google for Developers — [Neural Networks](https://developers.google.com/machine-learning/crash-course/neural-networks)
2. TensorFlow — [Neural Network Playground](https://playground.tensorflow.org/)
