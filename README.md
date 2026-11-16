# Sepam Intelligent Fault Detection

## Project Overview

This project focuses on developing an intelligent fault detection system for Schneider Electric Sepam protection relays using Artificial Intelligence and Image Processing.

The system analyzes images of relay screens, classifies screen types using a CNN model, extracts displayed information through OCR, and identifies potential warning messages.

## Technologies Used

- Python
- OpenCV
- PyTorch
- CNN (Convolutional Neural Network)
- EasyOCR
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Main Features

- Image preprocessing and screen extraction.
- Image enhancement using contrast and sharpness techniques.
- CNN-based classification of relay screens (Value / Warning).
- OCR-based extraction of numerical measurements.
- Detection and identification of warning messages.
- Support for predictive and preventive maintenance.

## Project Structure

- `notebooks/`: Jupyter Notebook containing the implementation.
- `models/`: Trained CNN model.
- `dataset/`: Dataset organization and instructions.
- `images/`: Project screenshots and results.

## Installation

```bash
pip install -r requirements.txt
```

## Execution

Open the notebook using Google Colab or Jupyter Notebook and execute the cells in order.

## Author

Developed as part of an Artificial Intelligence and Industrial Monitoring project.
