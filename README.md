# 🩺 DermaKnight
### AI-Powered Skin Cancer Detection Assistant

> "Empowering every doctor with the power of AI"

---

## 📋 Problem Statement
India has only 6,000 dermatologists for 1.4 billion people.
Primary care doctors see suspicious skin lesions daily but
have no accessible, free, explainable AI tool to assist them.
This causes delayed melanoma detection and preventable deaths.

---

## 💡 Solution
DermaKnight is a free AI tool that classifies skin lesions
as Malignant or Benign using MobileNetV2 CNN trained on
HAM10000 — with Grad-CAM heatmap showing exact suspicious
regions. Deployed via Streamlit + ngrok inside Google Colab.

---

## ✨ Key Features
- ✅ 85% accuracy on HAM10000 benchmark
- ✅ Grad-CAM heatmap explainability
- ✅ Streamlit web UI via ngrok public URL
- ✅ Completely free — no local setup needed
- ✅ Runs 100% on Google Colab

---

## 🛠️ Tech Stack
| Component      | Technology                     |
|----------------|--------------------------------|
| ML Model       | MobileNetV2 (Transfer Learning)|
| Dataset        | HAM10000 (10,015 images)       |
| Explainability | Grad-CAM                       |
| Framework      | TensorFlow / Keras             |
| UI             | Streamlit                      |
| Deployment     | ngrok (inside Colab)           |
| Development    | Google Colab                   |

---

## 📊 Model Performance
| Metric              | Score |
|---------------------|-------|
| Overall Accuracy    | 85%   |
| Benign Precision    | 89%   |
| Benign Recall       | 93%   |
| Malignant Precision | 65%   |
| Malignant Recall    | 54%   |

---

## 🚀 How to Run

### Step 1 — Open .ipynb file in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Wq-RZFtzC4uh7qWvsyTdYEDj7RE7IKGl)

### Step 2 — Enable GPU
Runtime → Change Runtime Type → T4 GPU

### Step 3 — Setup Kaggle
Upload your kaggle.json and run dataset download cells

### Step 4 — Run All Cells
Runtime → Run All

### Step 5 — Open Streamlit App
Copy the ngrok URL from the last cell output
and open it in your browser

---

## 📁 Dataset

| Source | Details |
|--------|---------|
| [HAM10000 — Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) | 10,015 dermatoscopic images across 7 skin lesion classes |
| [Tschandl et al., 2018 — Research Paper](https://doi.org/10.1038/sdata.2018.161) | Original paper: *The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions* |


---

## 📸 Results

### Grad-CAM Demo
![Grad-CAM](results/gradcam_demo.png)

### Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

### Training Curves
![Training](results/training_curves.png)

---

## ⚠️ Disclaimer
DermaKnight is a clinical decision-support tool for
healthcare professionals only. It is NOT a replacement
for professional medical diagnosis. Always consult a
qualified dermatologist for definitive diagnosis and
treatment.

---

## 👥 Team

| 🧑‍💻 Member | 🔗 GitHub | 💼 Role |
|:---:|:---:|:---:|
| **Astlejoe** | [![GitHub](https://img.shields.io/badge/GitHub-Astlejoe789-181717?style=flat&logo=github)](https://github.com/Astlejoe789) | 🤖 ML Model + Grad-CAM |
| **Harisha** | [![GitHub](https://img.shields.io/badge/GitHub-Harisha-181717?style=flat&logo=github)](https://github.com/24900903) | 🗂️ Data Preprocessing |
| **Daniyel** | [![GitHub](https://img.shields.io/badge/GitHub-Daniyel09-181717?style=flat&logo=github)](https://github.com/Daniyel09) | 🎨 Streamlit UI |
| **Jeyarikaran** | [![GitHub](https://img.shields.io/badge/GitHub-Jeyaarikaran-181717?style=flat&logo=github)](https://github.com/Jeyaarikaran) | 📝 Documentation |

---

## 📜 License
MIT License — free to use and modify
