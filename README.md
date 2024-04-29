# Parallelization-of-Image-Processing-Algorithms-for-Increased-Speedup---Barath-Kumar-and-Preethi

**Description**
This Jupyter notebook project is designed to run in Google Colab and includes scripts for mounting Google Drive, setting directory paths, and loading necessary Python libraries for data processing and machine learning. The project demonstrates the application of deep learning techniques for image processing tasks.
**Installation**
Ensure Python 3.6 or higher and the following packages are installed: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Seaborn, Scikit-Learn, and Scikit-Image. The project is designed to be run in a Google Colab environment, which provides most dependencies out of the box. However, you will need to ensure that you have access to Google Drive as it is used for storing and accessing datasets.

**To mount Google Drive and set up the environment, use the following Python code:**
from google.colab import drive
drive.mount('/content/drive')

# Setting up the directory
import os
os.chdir('/content/drive/My Drive/path_to_your_data')

# Import necessary libraries
import tensorflow as tf
import numpy as np
import cv2
import matplotlib.pyplot as plt

**Execution Instructions:**
Navigate to the dataset directory in your Google Drive. The code is set up to process images from specified directories for training, testing, and validation. Ensure the paths in the code match the locations of your datasets.

**Example command to run the script:**
cd /content/drive/My Drive/YourDatasetFolder
Main_code_speed.ipynb

