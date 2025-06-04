🧠 Skin Cancer Detection using Pretrained Models & Ensemble Learning
This project detects skin cancer from input images using 6 pretrained deep learning models — ResNet, GoogleNet, EfficientNet, MobileNet, VGG, and ImageNet. Each model predicts cancer type and outputs performance metrics like accuracy, precision, recall, F1-score, and confusion matrix.

Ensemble learning (hard and soft voting) is then applied to enhance the final prediction.


🔍 Features

Input: Skin lesion image

Output:

Predicted class (cancer/non-cancer)
Accuracy, Precision, Recall, F1-score
Confusion Matrix

Models used:

✅ ResNet
✅ GoogleNet
✅ EfficientNet
✅ MobileNet
✅ VGG
✅ ImageNet

Ensemble Voting:

🔘 Hard voting (majority prediction)
🔘 Soft voting (based on probabilities)

📁 Dataset

Trained and tested on the HAM10000 skin lesion dataset.

✅ How to Use

Open the Colab notebook.
Upload or select a test image.
Run the notebook cells to get predictions and evaluation metrics.
View individual model results and ensemble outcome.

📊 Sample Output

Confusion Matrix
Accuracy, Precision, Recall, F1-Score
Final ensemble prediction

