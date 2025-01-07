# Handwritten Chars Classification

A machine learning project for detecting and classifying handwritten alphabets using neural networks. This project leverages TensorFlow for model development and training, enabling high accuracy on handwritten datasets.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Model and Dataset Details](#model-and-dataset-details)

## Features

- **Multi-class classification**: Recognizes a wide range of handwritten alphabets.
- **Neural Network Design**: Implements multiple neural network architectures to optimize performance.
- **Data Preprocessing**: Includes data normalization, visualization, and efficient splitting into training, testing, and validation datasets.
- **Evaluation Metrics**: Reports accuracy, loss, and error metrics.

## Installation

### Prerequisites

- Python 3.x
- TensorFlow (recommended version: 2.x)
- Jupyter Notebook
- Required Python libraries: `numpy`, `matplotlib`, `scikit-learn`

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/KareemMagdy55/handwritten-alphabets-detector.git
    cd handwritten-alphabets-detector
    ```

2. (Optional) Set up a virtual environment:

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate
    ```

## Usage

1. Open the Jupyter Notebook:

    ```bash
    jupyter notebook Handwritten_alphabets_detector.ipynb
    ```

2. Follow the instructions in the notebook to preprocess data, train models, and evaluate results.

3. To run experiments, execute cells in the logical order provided in the notebook.

## Model and Dataset Details

- **Dataset**: Handwritten alphabet images (preprocessed for classification tasks).
- **Neural Network Architectures**:
  - First model: Simple feedforward neural network.
  - Second model: Deep CNN with dropout layers for regularization.

### Data Preprocessing

- Normalize pixel values to the range [0, 1].
- Visualize data distribution across classes.
- Split the dataset into training (70%), validation (20%), and testing (10%).
