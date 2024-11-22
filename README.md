# VQ-BeT TinyGrad Notebook

This repository contains a Jupyter notebook implementing VQ-BeT (Vector Quantized Behavior Transformer) using TinyGrad.

## What is VQ-BeT?

VQ-BeT is an advanced AI model for robot learning. It combines vector quantization and transformer architectures to help robots learn complex behaviors from demonstrations. VQ-BeT processes sequences of actions and observations, encoding them into discrete tokens. These tokens are then used to train a transformer model, which can generate new sequences of actions for the robot to perform. This approach allows robots to learn and generalize from a small number of demonstrations, making it efficient for various robotic tasks.

## Notebook Structure

This notebook interleaves explanatory text with executable code blocks:

1. Detailed explanations of VQ-BeT concepts and implementation details
2. Code snippets implementing various components of the VQ-BeT model
3. Visualizations and examples to illustrate key concepts
4. Step-by-step implementation of the VQ-BeT algorithm using TinyGrad

## Quick Start

To run this notebook:

1. Ensure you have Jupyter Lab installed
2. Install TinyGrad version 0.9.2:
   ```bash
   pip install tinygrad==0.9.2
   ```
   **Note:** TinyGrad 0.9.2 is required as the `Tensor.realize` function in version 0.10.0 is incompatible with this notebook.
3. Clone this repository:
   ```bash
   git clone https://github.com/mdaiter/vbet-tinygrad-notebook.git
   ```
4. Navigate to the repository directory:
   ```bash
   cd vbet-tinygrad-notebook
   ```
5. Start Jupyter Lab:
   ```bash
   jupyter-lab
   ```
6. Open the VQ-BeT notebook and start exploring!

Citations:
[1] https://github.com/mdaiter/vbet-tinygrad-notebook
