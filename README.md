# Tutorial
A simple tutorial for image classification with CIFAR10 dataset.

## Requirements
- Python package:
  - pytorch
  - tensorboardX
  - sklearn

## Usage
- Prepare dataset
  - Download CIFAR10 dataset from https://drive.google.com/open?id=1i11j8oxe_oBLOiRwT7XGhxLcwIWW8O21 (CIFAR10.zip)
  - Unzip CIFAR10.zip then put the train and test folders into ./Tutorial/datasets/CIFAR10
- Training
  ```
  cd Tutorial
  python3 train.py -e exp1_ResNet18
  ```

- Testing
  ```
  python3 test.py -e exp1_ResNet18 -w model_weights
  ```
