
# Deep Neural Network Gradient Calculation and Verification

This repository contains code for demonstrating the forward and backward passes in a simple neural network using PyTorch. It also includes verification of the computed gradients against the automatic gradients provided by PyTorch's autograd.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/RianaH/Deep_Neural_Network_Gradients.git
   cd Deep_Neural_Network_Gradients
   ```

2. Install the required dependencies:
   ```bash
   pip install torch matplotlib
   ```

## Usage

To run the Jupyter Notebook, use the following command:
   ```bash
   jupyter notebook Deep\ Neural\ Network\ Gradient\ Calculation\ and\ Verification.ipynb
   ```

## Description

The notebook is divided into several sections:

- **Setup**: Importing libraries and generating random data for the demonstration.
- **Forward Pass**: Performing the forward pass through the network and computing the loss.
- **Layer Outputs Visualization**: Visualizing the outputs of each layer after the forward pass.
- **Manual Backward Pass**: Manually computing the gradients using backpropagation.
- **Autograd Backward Pass**: Using PyTorch's autograd to compute the gradients.
- **Gradient Verification**: Verifying the manually computed gradients against the autograd gradients.
- **Gradient Visualization**: Visualizing the manually computed gradients and the autograd gradients for comparison.
