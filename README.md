# Handwritten Digit Recognition - Deep Learning Project

This project aims to recognize handwritten digits using a convolutional neural network (CNN). The dataset used is the MNIST dataset which contains 60,000 training images and 10,000 testing images of handwritten digits (0-9) in a 28x28 pixel format.

There are also 20 self created images that I created to manually test the model.

## Usage

Execute this command to use the same virtual environment that I used. This will also install all the packages that I used and the right versions.

```bash
pipenv install
```

Open the ``main.py`` file and run all the cells inside the file. If you don't want to run all the cells and retrain/retest the model, then you can jump to the indicated cell that loads an already trained model.

These cells have already been executed, so the output is already visible.

## Results

The trained model has a loss of ``0.0392...`` and an accuracy of ``0.9883...``

Using my own created digits the model managed to correctly classify ``17/20`` images.
