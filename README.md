# 🧠 Brain Tumor Classification using Deep Learning

A deep learning project for automatic classification of Brain MRI images into four tumor categories using Convolutional Neural Networks (CNN) and Transfer Learning with **EfficientNetV2-S**.

The project covers the complete machine learning pipeline, from data preprocessing to model evaluation, achieving **98.67% test accuracy** with excellent generalization.

---

## 📌 Project Overview

Brain tumor diagnosis from MRI scans is a challenging task that requires expert knowledge. This project leverages Deep Learning to automate the classification of brain MRI images into four classes:

- 🧠 Glioma
- 🧠 Meningioma
- 🧠 Pituitary Tumor
- ✅ No Tumor

---

## 🚀 Features

- MRI Image Classification
- Data Inspection & Exploratory Data Analysis
- Image Preprocessing
- Dataset Splitting
- Custom CNN Baseline Model
- Transfer Learning using EfficientNetB0
- Fine-Tuned EfficientNetV2-S Model
- Performance Evaluation
- Confusion Matrix
- Classification Report
- Overfitting Analysis

---

## 📂 Repository Structure

```
brain-tumor-classification/
│
├── 01_data_inspection.ipynb
├── 02_eda.ipynb
├── 03_preprocessing.ipynb
├── 04_dataset_split.ipynb
├── cnnmodel.ipynb
├── 05_transfer_learning_efficientnet.ipynb
├── EfficientNetV2S.ipynb
├── brain_tumor_improvement.ipynb
├── Data_Split.ipynb
├── README.md
└── requirements.txt
```

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains Brain MRI images belonging to four categories:

| Class |
|--------|
| Glioma |
| Meningioma |
| Pituitary Tumor |
| No Tumor |

### Dataset Split

| Dataset | Images |
|----------|-------:|
| Training | 7,392 |
| Validation | 1,584 |
| Test | 1,584 |
| **Total** | **10,560** |

---

## 🧪 Models Implemented

### 1. Custom CNN
- Baseline model
- Initial performance comparison

### 2. EfficientNetB0
- Transfer Learning
- Fine-Tuning
- Improved classification accuracy

### 3. EfficientNetV2-S (Final Model)
- Optimized architecture
- Fine-tuned for Brain MRI classification
- Best performing model

---

## 📈 Final Results

| Metric | Score |
|--------|-------:|
| Validation Accuracy | **98.99%** |
| Test Accuracy | **98.67%** |
| Macro F1-Score | **0.9865** |
| Weighted F1-Score | **0.9867** |

### Per-Class Accuracy

| Class | Accuracy |
|--------|---------:|
| Glioma | **99.29%** |
| Meningioma | **96.59%** |
| Pituitary | **98.86%** |
| No Tumor | **99.51%** |

---

## 📉 Model Performance

- ✅ Correct Predictions: **1563**
- ❌ Wrong Predictions: **21**
- 📉 Error Rate: **1.33%**

---

## 🔍 Overfitting Analysis

| Metric | Value |
|--------|-------:|
| Train Accuracy | 99.10% |
| Validation Accuracy | 98.99% |
| Test Accuracy | 98.67% |

**Observation**

- Small train-validation gap
- Small validation-test gap
- Good generalization
- No significant overfitting

---

## ⚙️ Training Details

- Framework: TensorFlow / Keras
- GPU: NVIDIA RTX 3050 Ti
- Training Time: ~45 minutes
- Saved Model: `best_efficientnetv2s.keras`

---

## 🔮 Future Improvements

- Deploy using Flask or Streamlit
- Grad-CAM Explainable AI
- Hyperparameter Optimization
- Docker Deployment
- REST API Integration
- Medical Report Generation

---

## 👨‍💻 Author

**Abdul Hafeez**

M.Sc. Computer Science (Data Analytics)

Rajagiri College of Social Sciences

GitHub: https://github.com/abdl-hafeez07

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.