# Face Recognition with Siamese Neural Network

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)](https://www.tensorflow.org/)
[![GitHub issues](https://img.shields.io/github/issues/Charantej07/Face-Recognition)](https://github.com/Charantej07/Face-Recognition/issues)
[![GitHub stars](https://img.shields.io/github/stars/Charantej07/Face-Recognition)](https://github.com/Charantej07/Face-Recognition/stargazers)

Face Recognition project using a Siamese Neural Network (SNN) for image verification. The SNN determines if two images are of the same person, suitable for facial recognition tasks.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository contains the implementation of a Siamese Neural Network for facial recognition and image verification. It uses TensorFlow and Keras for deep learning operations and provides tools for training, evaluating, and real-time verification using webcam capture.

---

## Features

- **Data Preparation**: Scripts to download and prepare datasets, including organizing images into positive, negative, and anchor categories.
- **Model Architecture**: Implementation of a Siamese network with custom layers for distance calculation and binary classification.
- **Training**: Code for training the SNN with binary cross-entropy loss and Adam optimizer.
- **Evaluation**: Tools to evaluate the model's performance using precision, recall, and confusion matrix visualization.
- **Real-time Verification**: Scripts to capture images via webcam for real-time verification against a set of known images.

---

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Charantej07/Face-Recognition.git
    cd Face-Recognition
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Dataset**:
   ```bash
    !wget http://vis-www.cs.umass.edu/lfw/lfw.tgz
    !tar -xf lfw.tgz
   ```
   Download the dataset and extract it into the appropriate directories (`data/positive`, `data/negative`, `data/anchor`).

---

## Usage

While Capturing Images, Press `v` to capture and verify an image from webcam, and `q` to quit.

---

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests for any improvements or suggestions you have.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

