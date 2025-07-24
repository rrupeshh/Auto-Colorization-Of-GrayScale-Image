# Auto Colorization of Gray Scale Image using CNN

## Overview

This project implements automatic colorization of grayscale images using Convolutional Neural Networks (CNN). The repository includes both basic auto-colorization and an advanced **Ethnicity Aware Autocolorization** system that considers ethnic characteristics for more accurate and culturally sensitive colorization.

Complete Walkaround is covered in this blog:  [Auto-Colorization of Grayscale Images using CNN](https://rupeshpoudel.com.np/blog/auto-colorization-grayscale-images-cnn)

## Tools Used

- Python 3
- Keras
- Numpy
- Tensorflow

## Features

- **Standard Auto-Colorization**: Basic CNN-based colorization for general grayscale images
- **Ethnicity Aware Auto-Colorization**: Advanced pipeline that detects and considers ethnic characteristics for improved colorization accuracy
- Pre-trained models for immediate use
- Comprehensive testing and evaluation

## Repository Structure

- **Dataset**: Training and testing datasets
- **Screenshots**: Result demonstrations
- **result**: Output colorized images
- **Ethnicity Aware Autocolorization**: Advanced ethnic-aware implementation with specialized notebooks and models
- **Auto_color.ipynb**: Main colorization notebook
- **model.h5**: Pre-trained model
- **model.json**: Model architecture

## Dataset

Dataset is included in the folder named Dataset.

## Ethnicity Aware Autocolorization

The **Ethnicity Aware Autocolorization** folder contains an advanced implementation that:

- Detects ethnic characteristics in facial images
- Applies culturally appropriate colorization
- Includes specialized models and testing notebooks
- Features comprehensive evaluation using LPIPS metrics
- Contains multiple test datasets for different ethnic groups

Key files in this folder:

- `Colorization Final.ipynb`: Main colorization pipeline
- `Ethnic Detection Final.ipynb`: Ethnicity detection system
- `Final Testing Both Pipeline.ipynb`: Combined testing pipeline
- `Colorize.h5` and `ColorizeTuned.h5`: Pre-trained models

## Screenshot of Result

Left Column includes the input images and the right column includes the automatically colorized images using CNN.

![Result 1](Screenshots/1.png)

![Result 2](Screenshots/2.png)

![Result 3](Screenshots/3.png)

## Getting Started

1. Clone the repository
2. Install required dependencies: `pip install tensorflow keras numpy`
3. Run `Auto_color.ipynb` for basic colorization
4. Explore the `Ethnicity Aware Autocolorization` folder for advanced features

## Usage

For basic colorization:

```bash
jupyter notebook Auto_color.ipynb
```

For ethnicity-aware colorization:

```bash
cd "Ethnicity Aware Autocolorization"
jupyter notebook "Final Testing Both Pipeline.ipynb"
```
