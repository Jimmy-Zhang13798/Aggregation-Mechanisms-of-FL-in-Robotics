# Aggregation Mechanisms in Federated Learning for Robotic Visual Obstacle Avoidance

## Introduction
Welcome to the official code repository for our paper, "Aggregation Mechanisms in Federated Learning for Enhancing Robotic Visual Obstacle Avoidance." In this repository, you will find the necessary code to replicate our Federated Learning (FL) experiments aimed at improving visual obstacle avoidance in robotics.

## Repository Structure
- `mixed_fusion.ipynb`: The primary notebook that implements Federated Learning with various aggregation mechanisms for visual obstacle avoidance.
- `evaluation.ipynb`: This notebook is used for performance evaluation of the saved models.
- `draw.ipynb`: A notebook responsible for generating figures for the paper.
- `traditional_centralized_learning/`: This directory contains code for conducting traditional centralized learning for comparison with our FL approach.

## Getting Started

### Prerequisites
Ensure that your system meets the following requirements:

- Correct Cuda version compatible with your hardware
- Appropriate Python version
- Compatible version of PyTorch

### Environment Setup

1. Create a new conda environment:
   ```bash
   conda create -n fl python=x.x
   ```


2. Activate the new environment:
    ```bash
    conda activate fl
    ``` 

3. Dependencies Installation
    Install the required dependencies by running the following commands:
    ```bash
    conda install pytorch torchvision torchaudio cudatoolkit=xx.x -c pytorch -c nvidia
    conda install jupyter notebook
    conda install tqdm
    conda install scikit-learn
    conda install matplotlib
    conda install tensorboard

    ``` 
    Please replace python=x.x and cudatoolkit=xx.x with the versions that match your system.


### Usage
Make sure to activate the conda environment before launching Jupyter Notebook. Then just simply run our codes.


### Contributing
We welcome contributions to this project. Please fork the repository and submit a pull request for review.

### License
Distributed under the MIT License. See LICENSE for more information.

### Contact
For any queries regarding the code or the paper, please open an issue in this repository.

### Acknowledgments

The authors wish to thank doctoral student Xianjia Yu for his support and assistance.