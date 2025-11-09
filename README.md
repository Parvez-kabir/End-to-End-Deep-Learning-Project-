# End-to-End-Deep-Learning-Project-
Potato Leaf Disease Classification (Acc: ~92%)
![Uploading image.png…]()

1. Project Overview
This project implements a Deep Convolutional Neural Network (CNN) using Transfer Learning to accurately classify seven different categories of potato leaf conditions, including various diseases and healthy states. The goal is to provide a robust, automated tool for early detection of agricultural threats, helping farmers take timely action to prevent crop loss.

The final model, based on the DenseNet121 architecture, achieved a high classification accuracy (approximately 92%, based on the filename).

2. Methodology and Model
A. Architecture
Base Model: DenseNet121 (Pre-trained on ImageNet).

Approach: Transfer Learning. The pre-trained DenseNet121 was used as the feature extraction base, and new layers were added on top for classification.

Framework: TensorFlow and Keras.

B. Hyperparameters
The model was configured with the following key parameters:

Image Size: 256x256 pixels

Batch Size: 32

Channels: 3 (RGB)

Epochs: 50

Optimizer: Adam

3. Dataset and Classes
A. Dataset Source
The model was trained on the "Potato Leaf Disease Dataset in Uncontrolled Environment" dataset. The dataset contains 3076 files for training and evaluation.

B. Classification Classes
The model classifies images into 7 distinct categories:

Bacteria

Fungi

Healthy

Nematode

Pest

Phytopthora

Virus

4. Requirements
To run this project and reproduce the results, you will need the following key libraries:

tensorflow (and tensorflow.keras)

numpy

pandas

matplotlib and seaborn (for visualization)

scikit-learn (for evaluation metrics)

plotly (for interactive plots)

Setup Instructions
Clone this repository.

Install the required packages.

Download and organize the dataset locally (or link it appropriately if running on a platform like Kaggle).

Run the notebook potato-leaf-diseases-acc-92.ipynb.
