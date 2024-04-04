
---

# PyTorchCIFAR10

This repository contains a Jupyter Notebook for classifying images from the CIFAR10 dataset using a convolutional neural network (CNN). The notebook is designed to be a comprehensive guide, covering everything from setting up your environment, data preprocessing, model creation, training, and evaluation.

## Getting Started

To get started, clone this repository to your local machine or Google Colab environment.

```bash
git clone https://github.com/pramodyasahan/PyTorchCIFAR10.git
```

## Dependencies

Before running the notebook, ensure you have the following dependencies installed:

- torch
- torchvision
- tqdm
- matplotlib

You can install these dependencies using pip:

```bash
pip install torch torchvision tqdm matplotlib
```

## Quick Start

1. **Set Up Your Environment:** Ensure that you are running the notebook in an environment where the dependencies listed above are installed. If you're using Google Colab, these dependencies are already available.

2. **Import Necessary Dependencies:** The notebook starts by importing all the necessary libraries, including `torch`, `torchvision`, `tqdm`, and `matplotlib`.

3. **Device Configuration:** Make sure to configure the device for training. The notebook is set up to use CUDA if available; otherwise, it falls back to CPU.

4. **Data Preprocessing:** The notebook provides detailed steps for data preprocessing, including defining transforms for training and test data.

5. **Model Training and Evaluation:** Follow the steps in the notebook to train and evaluate your CIFAR10 classifier.

## Support

If you encounter any issues or have questions, please open an issue in this GitHub repository.

---
