# Pneumonia Detection Using Chest X-Ray Images

### 📌 Project Overview
This project implements a **deep learning-based classifier** that automatically detects the presence of **pneumonia** from chest X-ray images using a convolutional neural network (CNN) model trained and evaluated in Google Colab.

The main goal is to build a binary classifier that can distinguish between **normal** and **pneumonia-affected** chest X-ray scans using image features extracted by a deep learning model.

---

## 📁 Project Contents
| File | Description |
|------|-------------|
| `chestxrayusingvgggfinalthesis.ipynb` | Main Jupyter Notebook containing the full implementation (data preprocessing, model training, evaluation, results) |
| `README.md` | Project documentation |

---

## 🧠 Methodology

1. **Dataset:**  
   A publicly available chest X-ray dataset with images labeled as *Normal* or *Pneumonia*. The dataset is typically organized into train/test/validation folders with respective subfolders for each class. :contentReference[oaicite:1]{index=1}

2. **Model Architecture:**  
   - Convolutional Neural Network (CNN)  
   - Preprocessing: image resizing, normalization, class balancing  
   - Training done in Google Colab with GPU acceleration

3. **Evaluation Metrics:**  
   - Accuracy  
   - Loss  
   - Confusion Matrix  
   - (Optional) ROC / AUC

---

## 🚀 How to Run

### 🧾 Option 1 — Google Colab
1. Open the notebook in Google Colab  
2. Mount your dataset (from Kaggle or Google Drive)  
3. Run all cells to preprocess, train, and evaluate the model

### 🖥️ Option 2 — Download & Local
1. Clone the repository:
   ```bash
   git clone https://github.com/Nafi-ruet-ece/Pneumonia_detection_using_X-ray.git
