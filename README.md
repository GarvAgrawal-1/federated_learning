# Federated Learning for Image Classification

This project demonstrates federated learning for image classification using a convolutional neural network (CNN) and the Flower (FLWR) framework. The notebook is designed for Google Colab and walks through data preparation, model definition, federated training, and evaluation.

## Features

- Implements federated learning using the Flower framework
- Trains a CNN on the MNIST dataset across multiple simulated clients
- Aggregates model updates on a central server
- Evaluates global model performance after federated rounds

## Dataset

- **MNIST Handwritten Digits Dataset**
- 60,000 training images and 10,000 test images of handwritten digits (0-9)
- Automatically downloaded and preprocessed in the notebook

## Usage

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1QFvOBD4d7otRo4QK90ovbI70ZcDA8dR-).
2. Run all cells in order to:
   - Load and preprocess the dataset
   - Define the CNN model architecture
   - Simulate federated learning with multiple clients
   - Evaluate the aggregated global model

## Requirements

- Python 3.x
- TensorFlow or PyTorch (as used in the notebook)
- Flower (`flwr`)
- NumPy
- Matplotlib

Install dependencies with:

```bash
pip install flwr tensorflow numpy matplotlib
```


## Results

- The notebook reports accuracy and loss for the global model after each federated round.
- Visualizations of training progress and evaluation metrics are included.

## License

This project is for educational purposes.
