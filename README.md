# MNIST TensorFlow PoC

This repository contains a simple example of training a neural network using TensorFlow to classify handwritten digits from the MNIST dataset.

After executing the script, the output provides insights into the training process, including metrics such as loss and accuracy, as well as potentially additional information about the model's performance.

## Downloading this repo

```bash
git clone https://github.com/prostosmirienie/mnist-tensorflow-poc.git
cd mnist-tensorflow-poc
```

## Activation of the Python virtual environment

Then activate the virtual environment for the project:

```bash
python3 -m venv venv
source venv/bin/activate
```

## Installation of additional package used in the project

To run the code, you need to have the following package installed:

- TensorFlow

You can install these packages using pip:

```bash
pip install tensorflow
```

## Runing the script

```bash
python mist_nn.py
```

## Deactivation of the Python virtual environment

When you are finished working, you can deactivate the virtual environment:

```bash
deactivate
```

## Other reqirements

### Hardware requirements

~2GB disk space

### System setting

If you don't have much experience working with Python 3, below are detailed instructions on how to install everything you need to be abble and set up an environmentand run this project locally on Linux Debian.

```bash
sudo apt update
sudo apt install python3-full python3-venv python3-pip
```

