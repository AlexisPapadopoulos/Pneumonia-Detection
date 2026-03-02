# Pneumonia Detection using Deep Learning

Introduction
Pneumonia is a significant global health challenge, claiming a child's life every 39 seconds. It causes over 800,000 fatalities annually among children under five, surpassing deaths from HIV/AIDS, measles, and malaria combined. While chest X-rays are the standard diagnostic tool, accurate interpretation is difficult even for experts.

This project leverages Deep Learning (DL) to identify subtle patterns in medical imaging, providing AI-driven diagnostic support to help medical professionals achieve faster results and better patient outcomes.

Dataset
The project utilizes chest X-ray images to classify cases as either "Normal" or "Pneumonia." The dataset is sourced from Kaggle and processed within the notebook environment.

Technologies & Libraries
The following tools and libraries were used to develop this project:

Language: Python

Deep Learning Framework: TensorFlow / Keras

Data Manipulation: NumPy, Pandas

Visualization: Matplotlib, Seaborn

Image Processing: OpenCV (cv2)

Evaluation: Scikit-learn (metrics for accuracy, precision, recall, F1-score, and ROC/AUC)

Methodology
The project follows a structured machine learning pipeline:

Data Loading: Downloading and extracting data via the Kaggle API.

Preprocessing: Using ImageDataGenerator for data augmentation and normalization.

Modeling: Implementing and comparing state-of-the-art Deep Learning architectures, including:

VGG16

ResNet50

Optimization: Utilizing callbacks such as EarlyStopping, ReduceLROnPlateau, and ModelCheckpoint to enhance training efficiency.

Evaluation: Analyzing model performance through confusion matrices and classification reports.

Features
Class Weight Balancing: Addresses potential dataset imbalances using sklearn.utils.class_weight.

Transfer Learning: Employs pre-trained models (VGG16, ResNet50) to leverage established feature extraction capabilities.

Visualization: Includes progress tracking with tqdm and performance visualizations.

How to Run
Clone the repository.

Install the required dependencies:

Bash
pip install tensorflow pandas seaborn matplotlib opencv-python scikit-learn tqdm
Ensure you have your kaggle.json API key for data downloading.

Run the Jupyter notebook Deep learning.ipynb.

Author
Alexios Papadopoulos - Master's Project
