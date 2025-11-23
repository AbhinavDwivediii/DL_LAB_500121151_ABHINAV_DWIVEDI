# Deep Learning Experiments








A comprehensive collection of deep learning experiments from fundamentals to advanced applications

                     View Experiments • Setup • Technologies

📋 Table of Contents

About
Repository Structure
Experiments
Setup & Installation
Technologies Used

🎯 About

This repository contains hands-on implementations of deep learning concepts, covering everything from basic neural network components to advanced transfer learning techniques.
Each experiment is designed to build practical understanding through implementation and analysis.

📁 Repository Structure

📦 Deep-Learning-Experiments


┣ 📂 Exp_1

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_2

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_3

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_4

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_5

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_6

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_7

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images


┣ 📂 Exp_8

┃ ┣ 📓 experiment.ipynb

┃ ┣ 📂 datasets

┃ ┗ 📂 images

┗ 📄 README.md


Each experiment folder is self-contained with its notebook, datasets, and generated visualizations.

🔬 Experiments

📊 Experiment 1

Comparative Study of Deep Learning Frameworks

Topics:

├── TensorFlow Implementation

├── Keras Implementation

├── PyTorch Implementation

└── Framework Comparison

Compare TensorFlow, Keras, and PyTorch by implementing linear regression.
Analyze code verbosity, API design patterns, and debugging capabilities across frameworks.


🔧 Experiment 2

Neural Networks from Scratch

Topics:

├── Single Neuron (AND Gate)

├── Feedforward Network (XOR)

├── MLP with Backpropagation

└── Activation & Loss Functions

Build neural network components from ground up without high-level libraries.
Implement forward propagation, backpropagation, and training mechanisms.


🎯 Experiment 3

Classification with DL Frameworks

Topics:

├── Dataset: MNIST / Fashion-MNIST

├── Data Preprocessing

├── Model Training & Validation

└── Performance Evaluation

End-to-end classification pipeline including data normalization, model building, training curves, and confusion matrix analysis.


🖼️ Experiment 4

Transfer Learning for Image Classification

Topics:

├── Pretrained Models

├── Feature Extraction

├── Fine-Tuning Strategies

└── Cats vs Dogs / CIFAR-10

Leverage pretrained models (ResNet, EfficientNet, MobileNet) for image classification.
Implement feature extraction and fine-tuning approaches.


⚡ Experiment 5

Training Deep Networks

Topics:

├── Activation Functions Visualization

├── Loss Functions Implementation

├── Backpropagation Algorithm

└── Optimizer Comparison

Visualize activation and loss functions.
Implement and compare optimizers like SGD, Momentum, and Adam.


🔷 Experiment 6

Multi-Layer Perceptron

Topics:

├── MLP Architecture Design

├── Layer Configuration

├── Hyperparameter Tuning

└── Classification Tasks

Build and train MLP architectures with various configurations.


🖥️ Experiment 7

Convolutional Neural Networks

Topics:

├── Convolution Operations

├── Pooling Layers (Max, Average)

├── Feature Map Extraction

└── CNN Architecture Design

Implement CNN components from scratch.
Visualize feature maps and understand convolution/pooling.


🎨 Experiment 8

CNN with Data Augmentation

Topics:

├── Data Augmentation Techniques

├── Image Transformations (Rotation, Flip, Zoom)

├── CNN Model Training

└── Performance Comparison

Implement CNNs with augmentation strategies to improve model generalization.


🛠️ Setup & Installation

Prerequisites

Python 3.8+

VS Code

GPU (Optional, for faster training)


Installation Steps

1. Clone the repository

git clone <repository-url>

cd deep-learning-experiments

2. Create virtual environment

python -m venv environment_name

Activate environment

Windows:

environment_name\Scripts\activate

Linux:

source environment_name/bin/activate

3. Install dependencies

pip install tensorflow keras torch torchvision numpy pandas matplotlib seaborn scikit-learn jupyter

4. Launch VS Code

Open experiment directory in VS Code

Running an Experiment

Navigate to experiment folder

cd Exp_1

Open the notebook

jupyter notebook experiment.ipynb

or use JupyterLab

jupyter lab experiment.ipynb

🔧 Technologies Used

Framework	Version	Purpose

TensorFlow	2.x	Deep Learning Framework

Keras	2.x	High-level Neural Networks API

PyTorch	2.x	Deep Learning Framework

NumPy	1.x	Numerical Computing

Pandas	2.x	Data Manipulation

Matplotlib	3.x	Data Visualization

Scikit-Learn	1.x	Machine Learning Tools
🙏 Thank You!
