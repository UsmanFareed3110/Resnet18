# ResNet18 Model Training and Validation

This repository contains code for training and validating a ResNet18 model on a custom dataset using PyTorch. The code performs the following tasks:
1. Loads and trains the model using a training dataset.
2. Evaluates the model using a validation dataset.
3. Tracks the loss and accuracy for both training and validation phases.
4. Identifies and prints the first 4 misclassified samples from the validation dataset.

## Requirements

- Python 3.x
- PyTorch
- Dataset (Train and Validation)

You can install the necessary dependencies using `pip`:

```bash
pip install torch torchvision
