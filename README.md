# MNIST TensorFlow PoC

This repository contains a simple example of training a neural network using TensorFlow to classify handwritten digits from the MNIST dataset.

## Downloading this repo

```bash
git clone https://github.com/prostosmirienie/mist-tensorflow-poc.git
cd mist-tensorflow-tutorial

```

## Reqirements and runing the Python virtual environment

### Hardware requirements

3GB disk space

### Environment setting

If you don't have much experience working with Python 3, below are detailed instructions on how to install everything you need to be abble and set up an environmentand run this project locally on Linux Debian.

```bash
sudo apt update
sudo apt install python3-full python3-venv python3-pip
```

Then activate the virtual environment for the project:

```bash
python3 -m venv venv
source venv/bin/activate
```

### Installation of additional packages used in the project

To run the code, you need to have the following packages installed:

- TensorFlow
- NumPy
- Matplotlib

You can install these packages using pip:

```bash
pip install tensorflow numpy matplotlib
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

