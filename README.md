# Super Resolution Generative Adversarial Network (SRGAN) for Image Quality Enhancement

## Overview

This repository contains the implementation of a Super Resolution Generative Adversarial Network (SRGAN) aimed at enhancing image quality through deep learning techniques. The project utilizes the DIV2K dataset, which serves as a benchmark for super-resolution research, to train and evaluate the model's performance in upscaling low-resolution images.

## Key Features

- Implementation of the SRGAN architecture.
- Training using the DIV2K dataset, which includes 2,000 high-resolution images.
- Visualization of results comparing low-resolution, generated, and high-resolution images.

## Dataset

The DIV2K dataset is widely recognized as a benchmark for super-resolution tasks, containing high-resolution images suitable for training and evaluating super-resolution algorithms. It is divided into training, validation, and test subsets to ensure robust evaluation.
https://data.vision.ee.ethz.ch/cvl/DIV2K/

## Requirements

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- PIL

You can install the required packages using pip:

```bash
pip install tensorflow numpy opencv-python matplotlib pillow

