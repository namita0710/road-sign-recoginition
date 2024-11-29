# Road Sign Recognition

## Overview

The **Road Sign Recognition** project is a machine learning solution designed to classify traffic signs from images. This project demonstrates the use of deep learning techniques, particularly Convolutional Neural Networks (CNNs), for image recognition tasks. It can be used in real-world applications like self-driving cars, driver assistance systems, and traffic monitoring.

---

## Features

- Identifies and classifies various road signs accurately.
- Uses a labeled dataset of traffic signs for training and testing.
- Visualizes training and validation accuracy and loss graphs.
- Provides detailed insights into the model's performance.

---

## Dataset

The project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset, which contains over 50,000 labeled images of traffic signs across 43 classes.

- **Dataset Location:** [GTSRB Dataset](https://benchmark.ini.rub.de/gtsrb_dataset.html)
- **Structure:**
  - Training Set: ~39,000 images
  - Test Set: ~12,000 images

----

## Model and Training

The model is a Convolutional Neural Network (CNN) designed to classify traffic signs with high accuracy. Key steps include:

1. Preprocessing images (resizing, normalization).
2. Splitting the dataset into training, validation, and testing subsets.
3. Training the CNN with augmented data to improve generalization.
4. Plotting accuracy and loss graphs for performance evaluation.

---

## Prerequisites

Ensure the following tools and libraries are installed:

- **Python 3.9+**
- **Libraries:**
  - `numpy`
  - `tensorflow` or `keras`
  - `matplotlib`
  - `pandas`
  - `scikit-learn`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/namita0710/RoadSignRecognition.git
   cd RoadSignRecognition
