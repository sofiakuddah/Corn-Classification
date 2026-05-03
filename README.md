# Corn Leaf Disease Classification 🌽

This repository contains a Deep Learning project for classifying corn leaf conditions using the **MobileNetV3-Small** architecture in PyTorch. It was developed to accurately identify plant health states and diseases, achieving outstanding evaluation metrics on the test dataset.

## 🚀 Project Overview

The main objective of this project is to automate the detection of diseases in corn leaves. By utilizing a lightweight and efficient Convolutional Neural Network (CNN) architecture—MobileNetV3-Small—the model can perform rapid inferences while maintaining high accuracy, making it suitable for edge devices or mobile applications.

### Key Highlights
- **Architecture:** PyTorch implementation of `MobileNetV3-Small`.
- **Performance:** Achieved excellent precision and recall on the test set, with perfect predictions on the final evaluation batch.
- **Data Pipeline:** Built with custom PyTorch DataLoaders, robust image transformations (augmentation), and disciplined dataset splitting for reliable training.

## 📁 Repository Structure

- `corn_classification.ipynb` - The main Jupyter Notebook containing the complete end-to-end pipeline (Data Cleaning, Preprocessing, Model Building, Training, Validation, and Evaluation).
- `Laporan_Corn_Classification.docx` - The comprehensive project report documenting the methodology, experiments, and results (in Indonesian).

## 🛠️ Tech Stack

- **Python**
- **PyTorch & Torchvision** (Model Architecture, DataLoader, Transforms)
- **Matplotlib** (Data Visualization)
- **NumPy & Pandas** (Data Manipulation)
- **Scikit-learn** (Metrics & Evaluation)

## 📊 Methodology

1. **Data Preprocessing & Augmentation:** Images were cleaned, resized, normalized, and augmented to improve model generalization and prevent overfitting.
2. **Model Training:** Utilized the `MobileNetV3-Small` architecture, optimizing with standard loss functions and optimizers for image classification.
3. **Evaluation:** The model was rigorously validated during training and tested on an unseen holdout set. The notebook includes detailed visualizations of the model's predictions.

---
*This project is part of a Machine Learning & Data Science portfolio by Zalsa.*
