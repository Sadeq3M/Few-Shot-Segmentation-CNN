# Indoor Scene Recognition Using Deep Learning

This project implements a deep learning pipeline for **indoor scene recognition** using the [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com). The goal is to classify complex indoor environments by leveraging both **global spatial layouts** and **local object-level features**.

## 🧠 Project Overview

We designed and trained deep learning models to recognize and differentiate between various indoor scenes (e.g., library, kitchen, bedroom) with high accuracy, overcoming the limitations of traditional scene classifiers.

### 🔍 Key Features

- Utilizes **Convolutional Neural Networks (CNNs)** to extract spatial and texture-based features.
- Integrates **Recurrent Neural Networks (RNNs)** to model sequential dependencies and context within scenes.
- Focuses on **object recognition**, **semantic boundary detection**, and **scene classification**.
- Trained and evaluated on the **MIT Indoor Scenes Dataset**, which contains over 15,000 images across 67 categories.

## 📁 Dataset

- Dataset: [MIT Indoor Scenes](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com)
- Contains 67 indoor categories (e.g., bookstore, gym, restaurant, office).
- Highly diverse scenes with cluttered environments and varied lighting conditions.

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch
- NumPy, OpenCV, Matplotlib

(You can install dependencies using a `requirements.txt` file if needed.)

## 🚀 How to Run

1. Download the [MIT Indoor Scenes Dataset](https://web.mit.edu/torralba/www/indoor.html?ref=hackernoon.com) and extract it to your working directory.
2. Open the notebook `MIT_CNN_FSS_Final.ipynb` in Jupyter.
3. Follow the steps in the notebook for preprocessing, training, and evaluation.

## 📊 Results

- The model achieved promising accuracy on challenging indoor scenes.
- Qualitative results show effective detection of object boundaries and scene context.
- Future improvements could involve transformer-based architectures and attention mechanisms.

## 🧑‍💻 Author

This project was developed as part of a deep learning coursework project.

---

