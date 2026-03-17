# 🩺 DermaKnight
### AI-Powered Skin Cancer Detection Assistant

> "Empowering every doctor with the power of AI"
> Built for **Hack Hustle: Code Knight 2026** | HealthTech Domain
> Saveetha Engineering College

---

## 📋 Problem Statement
India has only 6,000 dermatologists for 1.4 billion people.
Primary care doctors see suspicious skin lesions daily but
have no accessible AI tool to assist them. Existing tools
are paid, inaccessible, and don't explain their decisions.
This causes delayed melanoma detection and preventable deaths.

---

## 💡 Our Solution
DermaKnight is a free, web-based AI tool that classifies
skin lesions as Malignant or Benign using MobileNetV2 CNN
trained on HAM10000 dataset — with Grad-CAM heatmap
explainability showing exactly where the AI found suspicion.

---

## ✨ Key Features
- ✅ 85% accuracy on HAM10000 benchmark dataset
- ✅ Grad-CAM heatmap — unique explainability feature
- ✅ Completely free — no subscription or installation
- ✅ Works on any browser and device
- ✅ Designed for India's primary healthcare settings

---

## 🛠️ Tech Stack
| Component | Technology |
|---|---|
| ML Model | MobileNetV2 (Transfer Learning) |
| Dataset | HAM10000 (10,015 images) |
| Explainability | Grad-CAM |
| Backend | TensorFlow / Keras |
| Frontend | Streamlit |
| Development | Google Colab + VS Code |

---

## 📊 Model Performance
| Metric | Score |
|---|---|
| Overall Accuracy | 85% |
| Benign Precision | 89% |
| Benign Recall | 93% |
| Malignant Precision | 65% |
| Malignant Recall | 54% |

---

## 🚀 How to Run

### 1. Clone the repo
git clone https://github.com/yourusername/DermaKnight.git
cd DermaKnight

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the app
streamlit run app/app.py

---

## 📸 Screenshots
[Add your UI screenshot here]
[Add your Grad-CAM result here]

---

## 📁 Dataset
- HAM10000 from Kaggle:
  https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000
- Original paper: Tschandl et al., 2018

---

## ⚠️ Disclaimer
DermaKnight is a clinical decision-support tool for
healthcare professionals only. It is NOT a replacement
for professional medical diagnosis. Always consult a
qualified dermatologist for definitive diagnosis.

---

## 👥 Team
| Name | Role |
|---|---|
| [Your Name] | ML Model + Grad-CAM |
| [Member 2] | Data Preprocessing |
| [Member 3] | Frontend UI |
| [Member 4] | Pitch + Documentation |

---

## 🏆 Built For
Hack Hustle: Code Knight 2026
HealthTech — The Vital Line Domain
Saveetha Engineering College, Chennai
