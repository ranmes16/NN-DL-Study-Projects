# Neural Networks and Deep Learning Projects

This repository is a collection of projects exploring neural networks and deep learning concepts. It serves as a learning journey through hands-on projects.

## Table of Contents

- [Overview](#overview)
- [Components](#components)
  - [Value Class](#value-class)
  - [Neuron Class](#neuron-class)
  - [Layer Class](#layer-class)
  - [MLP Class](#mlp-class)
- [Shoutout](#shoutout)

## Overview

This implementation provides a foundational understanding of how neural networks operate under the hood. It covers:
- Creating and manipulating neurons and layers.
- Implementing forward and backward propagation manually.
- Understanding and applying the concept of gradients for optimization.

## Components

### Value Class

The `Value` class is the core data structure for this implementation. It handles:
- Storing data and gradients.
- Supporting operations like addition, multiplication, and activation functions (tanh and exp).
- Implementing backward propagation for automatic differentiation.

### Neuron Class

The `Neuron` class represents a single neuron in the network. It includes:
- Initializing weights and bias.
- Forward pass using the tanh activation function.
- Aggregating parameters for gradient updates.

### Layer Class

The `Layer` class comprises multiple neurons. It handles:
- Initializing a specified number of neurons.
- Performing a forward pass for all neurons in the layer.
- Aggregating parameters from all neurons.

### MLP Class

The `MLP` (Multi-Layer Perceptron) class builds the entire network. It includes:
- Initializing multiple layers.
- Performing forward pass through all layers.
- Aggregating parameters from all layers.

## Shoutout

Special thanks to [Andrej Karpathy](https://www.youtube.com/watch?v=VMj-3S1tku0&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=1) for the amazing tutorial series that inspired and guided this implementation. His work made understanding neural networks much more approachable and fun.
