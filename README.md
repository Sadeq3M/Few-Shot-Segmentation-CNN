# Indoor Scene Recognition Using Deep Learning

This repository contains the final project titled **Indoor Scene Recognition Using Deep Learning**, which implements a pipeline for classifying complex indoor environments using the [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com).

We explore how combining **Convolutional Neural Networks (CNNs)** and **Recurrent Neural Networks (RNNs)** enables the model to capture both local object-level features and global spatial layout for improved scene classification.

## 🧠 Project Overview

The goal is to build a robust deep learning model capable of recognizing different types of indoor scenes — such as libraries, gyms, kitchens, and offices — where traditional methods often fail due to high intra-class variability and cluttered environments.

### 🔍 Key Features

- **CNN-based feature extraction** for capturing spatial and textural information.
- **RNN-based modeling** for understanding spatial context and sequential dependencies.
- Emphasis on **object recognition** and **boundary awareness** within scenes.
- Trained and tested on the [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com), containing 15,620 images across 67 scene categories.

## 📁 Dataset

- **Name:** [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com)  
- **Images:** 15,620 total  
- **Categories:** 67 indoor scene types  
- **Challenges:** Clutter, diverse lighting, and variable object configurations.

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch
- NumPy
- OpenCV
- Matplotlib

## 🚀 How to Run

1. Download the [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com) and place it in the project directory.
2. Open the notebook `MIT_CNN_FSS_Final.ipynb` using Jupyter.
3. Follow the cells to run preprocessing, training, evaluation, and visualization.

## 📊 Results

- The model shows strong performance in recognizing indoor scenes with complex spatial configurations.
- Visualization results demonstrate effective object detection and scene-level understanding.
- Future work could explore transformer-based models or attention mechanisms for further accuracy improvements.

## 🧑‍💻 Author

This project was developed as part of a graduate-level deep learning course.

---

