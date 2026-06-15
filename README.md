# MNIST Digit Recognition

## Overview
This project implements a handwritten digit recognition system using the MNIST dataset — a benchmark dataset of 70,000 grayscale images (28×28 pixels) of handwritten digits from 0 to 9.

We build a complete machine learning pipeline: loading and exploring the data, preprocessing, training a Logistic Regression classifier, and evaluating its performance using accuracy score and confusion matrix.

The model achieves 92.03% accuracy on the test set.

## Project Structure
```
mnist/
├── mnist.ipynb
└── README.md
```

## Prerequisites
- Python 3.10+
- VS Code with the Jupyter extension

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/ThomasLeboulanger/mnist
cd MNIST
```

### 2. Create and activate a virtual environment
```bash
python3 -m venv mnist-env
source mnist-env/bin/activate
```

### 3. Install dependencies
```bash
pip install numpy matplotlib scikit-learn
```

### 4. Open the notebook
Open `mnist.ipynb` in VS Code and run all cells in order.


Note 1: The dataset is downloaded automatically from OpenML on first run — no manual download required.
Note 2: SSL verification is disabled in the notebook to work around a macOS certificate issue. This is acceptable for a local learning project but should not be used in production.
