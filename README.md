# Handwritten Digit Detection System using YOLOv8

## Project Overview
This project focuses on detecting handwritten digits from images using the YOLOv8 (You Only Look Once) object detection model. The process involves generating synthetic training images, training a YOLOv8 model on them, and detecting handwritten digits from test images. The detected digits are stored in a CSV file with the image name and a list of detected numbers.

The project demonstrates the use of synthetic data generation, model training, and digit detection, with the results saved for further analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation Instructions](#installation-instructions)
- [How to Run the Code](#how-to-run-the-code)
  - [1. Generating Training Images](#1-generating-training-images)
  - [2. Training the YOLOv8 Model](#2-training-the-yolov8-model)
  - [3. Detecting Digits](#3-detecting-digits)
- [Output Structure](#output-structure)
- [Acknowledgments](#acknowledgments)

## Installation Instructions

Before running the code, ensure you have the required dependencies installed.

### 1. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/Atharvnagar007/OCR.git
cd handwritten-digit-detection
```
### 2.Generate Dataset
Once you run the code to make the manual dataset for the generation images with decimal places for better results.
### 3.Training the YOLOv8 Model
Once you have the training images, you can start training the YOLOv8 model which will take about 8-10 hours to train on the dataset for better results.
### 4. Output structure 
Saved in the csv file in the given format by the company.

### Acknowledgements
We would like to thank **Magnasoft** for providing the task and context that inspired the development of this project. Their support was crucial in shaping the scope and goals of our work.
