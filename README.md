German Traffic Sign Recognition Project
This notebook demonstrates the process of building, training, and evaluating convolutional neural networks (CNNs) for the German Traffic Sign Recognition Benchmark (GTSRB) dataset. It explores two different CNN architectures and the impact of data augmentation on model performance.

Table of Contents
Project Overview
Dataset
Getting Started
Prerequisites
Running the Notebook
Notebook Structure
Models
Results
License
Project Overview
The goal of this project is to classify traffic signs from images using deep learning techniques. We train and compare two different CNN models to recognize the various traffic signs present in the GTSRB dataset. Data augmentation is also applied to one of the models to improve its generalization capabilities.

Dataset
The German Traffic Sign Recognition Benchmark (GTSRB) dataset is used for this project. It contains over 50,000 images of traffic signs belonging to 43 classes. The dataset is downloaded directly within the notebook using the opendatasets library.

Getting Started
Prerequisites
Google Colab environment or a local Python environment with the following libraries installed:
tensorflow
keras
numpy
pandas
matplotlib
opencv-python (cv2)
Pillow (PIL)
opendatasets
scikit-learn (sklearn)
seaborn
requests
