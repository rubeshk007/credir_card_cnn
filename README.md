# credir_card_cnn
Fraud detection using a 1D CNN on an imbalanced credit card dataset. Includes preprocessing, under-sampling, model training, and evaluation with precision-recall curves, confusion matrix, and F1-score. Built with TensorFlow, pandas, scikit-learn, and matplotlib.

# 🕵️‍♂️ Credit Card Fraud Detection using CNN

This project focuses on detecting fraudulent credit card transactions using a 1D Convolutional Neural Network (CNN). Fraud detection is a binary classification challenge characterized by significant class imbalance—fraudulent transactions are rare compared to legitimate ones.

The workflow covers all key stages: data loading, preprocessing, balancing, model construction, training, and evaluation using industry-standard metrics.

---

## 🚀 Key Features

- Data preprocessing and feature scaling
- Class balancing through under-sampling
- Construction of a 1D CNN using TensorFlow/Keras
- Visualization of training and validation metrics
- Model evaluation using:
  - Confusion Matrix
  - Precision, Recall, and F1-Score
  - ROC-AUC Score
  - Precision-Recall Curve and threshold tuning

---

## 📁 Dataset

Dataset: [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) (Kaggle)

> **Note:** Dataset file (`creditcard.csv`) must be downloaded separately and placed in the appropriate working directory.

---

## 🧪 Technologies Used

- Python (3.x)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- TensorFlow/Keras

---

## 🧠 Model Architecture

- Input layer: 1D feature vector
- 1st Conv1D layer → Batch Normalization → Dropout
- 2nd Conv1D layer → Batch Normalization → Dropout
- Flatten layer
- Dense layer (ReLU) → Dropout
- Output Dense layer (Sigmoid)

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Precision-Recall Curve with optimal threshold selection

Optimal threshold is identified by maximizing F1-Score across all threshold values in the Precision-Recall curve.

---

## 📈 Visualizations

- Training vs Validation Accuracy and Loss
- Confusion Matrix Heatmap
- Precision-Recall Curve with optimal point highlighted

---

## 🏁 Usage Instructions

1. Clone this repository
2. Download and place the dataset (`creditcard.csv`) in the working directory
3. Run the script or notebook using Python or Google Colab
4. Monitor model training and view evaluation results

---

## 🤝 Contributions

Contributions are welcome. Feel free to submit issues or pull requests for improvements and bug fixes.

---

## 📜 License

This project is licensed under the MIT License.
