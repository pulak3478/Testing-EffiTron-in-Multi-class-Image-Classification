# 🚀 EffiTron: Eye Disease Classification Using EfficientNet + Transformer

This repository contains the implementation of **EffiTron**, a deep learning model that combines the EfficientNet backbone with Transformer encoder blocks to classify eye diseases into four classes:

- Cataract  
- Diabetic Retinopathy  
- Glaucoma  
- Normal  

The model is trained and evaluated on the Kaggle Eye Disease Dataset, with comprehensive performance analysis and visualization.

---

## 📋 Contents

- [Model Overview](#-model-overview)
- [🛠️ Setup Instructions](#️-setup-instructions)
- [🏃‍♂️ Training & Evaluation](#-training--evaluation)
- [🏆 Results](#-results)
- [📊 Visualizations](#-visualizations)
- [🚀 Usage](#-usage)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

## 📖 Model Overview
EffiTron leverages EfficientNet's feature extraction capabilities and the Transformer's global attention mechanism to improve classification accuracy on eye disease images.

---

## 🛠️ Setup Instructions

### ✅ Requirements
- Python 3.8+  
- TensorFlow 2.x / PyTorch 1.10+  
- torchvision (if using PyTorch)  
- matplotlib  
- scikit-learn  
- tqdm  
- seaborn  
- numpy  
## 📁 Dataset
Download and prepare the Kaggle Eye Disease Dataset from [https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification]

---

## 🏃‍♂️ Training & Evaluation
Run the training script:
eye_diseases_classification test with EffiTron.ipynb

## 🏆 Results
| Class                | Precision | Recall | F1-Score | Support |
| -------------------- | --------- | ------ | -------- | ------- |
| Cataract             | 0.92      | 0.98   | 0.95     | 208     |
| Diabetic Retinopathy | 1.00      | 1.00   | 1.00     | 220     |
| Glaucoma             | 0.93      | 0.94   | 0.94     | 303     |
| Normal               | 0.96      | 0.89   | 0.92     | 215     |
| **Overall Accuracy** |           |        | **0.95** | **946** |

## 📊 Visualizations

### Model Performance Over Epochs
Loss and accuracy curves during training and validation.

![Model Performance Over Epochs](./images/Model_Performance_Over_Epochs.png)
