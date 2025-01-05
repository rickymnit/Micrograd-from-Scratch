# Micrograd from Scratch: Forward and Backward Propagation with Graphviz

This repository implements a simple neural network framework from scratch in Python, focusing on forward and backward propagation. We also use **Graphviz** to visualize the computational graph of the neural network and the flow of operations.

## Overview

This project aims to build a neural network framework by implementing key components from scratch, including:

- **Forward propagation**: The process of calculating the output of the neural network based on the input and current weights.
- **Backward propagation**: The process of updating the weights in the network using gradients calculated by the chain rule.
- **Graphviz**: Visualizes the flow of operations in the computational graph, making the forward and backward propagation processes easier to understand.

This repository is a learning resource and is ideal for those looking to understand the inner workings of neural networks at a low level.

## Features

- Implemented **forward propagation** and **backpropagation** from scratch.
- Visualize the computational graph using **Graphviz**.
- Supports simple neural network architectures (single-layer and multi-layer).
- Gradient descent optimization for training the network.

## Cloning project

```bash
git clone https://github.com/rickymnit/Micrograd-from-Scratch.git
cd Micrograd-from-Scratch
```

## Installation

You need Python 3.6+ to run this project. You also need to install the following dependencies:

```bash
pip install numpy graphviz
```
