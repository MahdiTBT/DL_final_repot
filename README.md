# DL_final_repot
This repository contains the implementation of a Deep Learning model for crack propagation stage classification. It includes data preprocessing, CNN architecture, training, evaluation, and visualization scripts. Designed for reproducibility, the code is modular, efficient, and adheres to standard practices in PyTorch.

# Deep Learning Crack Propagation Detection

This repository contains the implementation of a Convolutional Neural Network (CNN) to classify crack propagation stages in materials. It includes scripts for data preprocessing, model training, evaluation, and visualization. Designed with modularity and efficiency, the code adheres to best practices in PyTorch.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [File Structure](#file-structure)
- [License](#license)

---

## Overview
Crack propagation classification is a critical task in structural health monitoring. This project implements a deep learning-based approach to classify cracks into stages, enabling efficient analysis and decision-making.

### Key Highlights:
- End-to-end pipeline: Data preprocessing, training, evaluation, and visualization.
- Uses PyTorch for model implementation and training.
- Implements metrics like confusion matrix and classification report.
- Visualization of successes and failures in predictions.

---

## Features
- **Custom CNN Architecture**: Designed for grayscale image classification.
- **Preprocessing**: Includes resizing, normalization, and augmentation.
- **Evaluation Metrics**: Accuracy, confusion matrix, and classification report.
- **Visualization**: Displays success and failure cases with clear labeling.
- **Reproducibility**: Seed initialization ensures consistent results.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/deep-learning-crack-detection.git
   cd deep-learning-crack-detection
