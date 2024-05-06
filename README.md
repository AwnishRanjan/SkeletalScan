# SkeletalScan

SkeletalScan is a deep learning project designed to classify bone images and detect fractures using the ResNet-50 architecture. It provides an automated system for analyzing medical images to identify the affected bone and determine if it is fractured.

## Overview

The project consists of two main tasks:

1. **Bone Classification:** Utilizing the ResNet-50 convolutional neural network (CNN) architecture to classify bone images into different categories based on the part of the body they belong to (e.g., femur, humerus, radius, etc.).

2. **Fracture Detection:** Performing binary classification to determine whether the identified bone is fractured or not.

## Dataset

The model is trained on a large dataset of medical images containing bone scans and corresponding labels indicating the bone type and fracture status. The dataset is preprocessed and split into training, validation, and testing sets to train and evaluate the model's performance.

## Technologies Used

- **Deep Learning Framework:** TensorFlow
- **Model Architecture:** ResNet-50
- **Programming Language:** Python
- **FrontEnd :** Tkinter 

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/skeletalscan.git
2. Install dependencies:
   ```bash
   cd skeletalscan
   pip install -r requirements.txt
3. Train the model:
   ```bash
   python training_fracture.py
   python training_parts.py
4. Evaluate the model :
   ```bash
   python prediction.py
5. Run the project on Tkinter
   ```bash
   python mainGUI.py
   
# Usage
- Training: Train the model using the provided dataset or your custom dataset by modifying the train_model.py script.
- Evaluation: Evaluate the trained model's performance on the testing dataset to assess its accuracy and performance metrics.
- Deployment: Deploy the trained model as a web service using Flask for real-time fracture detection on new bone images.
  
# Contributing
Contributions to improve the project are welcome! If you'd like to contribute, please follow these steps:
- Fork the repository.
- Create your feature branch: git checkout -b feature-name.
- Commit your changes: git commit -am 'Add some feature'.
- Push to the branch: git push origin feature-name.
- Submit a pull request.
