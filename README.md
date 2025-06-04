# 🧠 Skin Cancer Detection using Pretrained Models & Ensemble Learning

This project detects skin cancer from input images using 6 pretrained deep learning models — ResNet, GoogleNet, EfficientNet, MobileNet, VGG, and ImageNet.  
Each model predicts the cancer type and outputs performance metrics like accuracy, precision, recall, F1-score, and confusion matrix.

Ensemble learning (hard and soft voting) is then applied to improve the final prediction.

---

## 🔍 Features

- **Input:** Skin lesion image  
- **Output:**
  - Predicted class (cancer / non-cancer)
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix

---

## 🧠 Models Used

- ✅ ResNet  
- ✅ GoogleNet  
- ✅ EfficientNet  
- ✅ MobileNet  
- ✅ VGG  
- ✅ ImageNet

---

## 🗳️ Ensemble Voting Methods

- 🔘 Hard Voting – Majority prediction  
- 🔘 Soft Voting – Probability-based prediction

---

## 📁 Dataset

- **HAM10000** skin lesion dataset (Human Against Machine with 10,000 training images)

---

## 📖 How to Use

1. Open the Colab notebook.
2. Install necessary libraries.
3. Download and Upload Kaggle API Token (Required for dataset):
- Go to your Kaggle account.
- Click on your profile picture → Account Settings.
- Scroll down to the API section.
- Click “Create New API Token”.
- This will download a file named kaggle.json.
4. Upload this file in the Colab notebook when prompted (used to authenticate Kaggle access and download the dataset).
5. Once the dataset is downloaded and model is ready:
6. Run each cell in order and Upload any test image of a skin lesion.

---

## 📊 Sample Output

- Confusion Matrix  
- Accuracy, Precision, Recall, F1-Score  
- Final Ensemble Prediction
