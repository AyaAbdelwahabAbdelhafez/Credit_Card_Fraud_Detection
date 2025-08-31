# 💳 Credit Card Fraud Detection

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using **different resampling techniques** to handle imbalanced data.  
The dataset is highly imbalanced (fraud cases are much fewer than non-fraud cases), so techniques like undersampling, oversampling, SMOTE, and ensemble learning were applied to improve model performance.  

---

## ⚙️ Techniques Used
- **Imbalanced Dataset (Original)**  
- **Undersampling**  
- **Oversampling**  
- **SMOTE (Synthetic Minority Oversampling Technique)**  
- **Ensemble with Undersampling**  

---

## 📊 Results

### 🔹 Imbalanced Dataset (Original)
| Metric      | Class 0 (Normal) | Class 1 (Fraud) |
|-------------|------------------|-----------------|
| Precision   | 1.00             | 0.69            |
| Recall      | 1.00             | 0.73            |
| F1-Score    | 1.00             | 0.71            |
| Accuracy    | 1.00             | -               |

---

### 🔹 Undersampling
| Metric      | Class 0 | Class 1 |
|-------------|---------|---------|
| Precision   | 0.95    | 0.98    |
| Recall      | 0.98    | 0.95    |
| F1-Score    | 0.97    | 0.96    |
| Accuracy    | 0.96    | -       |

---

### 🔹 Oversampling
| Metric      | Class 0 | Class 1 |
|-------------|---------|---------|
| Precision   | 0.92    | 0.96    |
| Recall      | 0.96    | 0.92    |
| F1-Score    | 0.94    | 0.94    |
| Accuracy    | 0.94    | -       |

---

### 🔹 SMOTE
| Metric      | Class 0 | Class 1 |
|-------------|---------|---------|
| Precision   | 0.98    | 0.96    |
| Recall      | 0.96    | 0.98    |
| F1-Score    | 0.97    | 0.97    |
| Accuracy    | 0.97    | -       |

---

### 🔹 Ensemble with Undersampling
| Metric      | Class 0 | Class 1 |
|-------------|---------|---------|
| Precision   | 1.00    | 0.05    |
| Recall      | 0.97    | 0.92    |
| F1-Score    | 0.98    | 0.09    |
| Accuracy    | 0.97    | -       |

---
## 📝 Conclusion

The SMOTE technique provided the best balance between detecting frauds (Class 1) and non-frauds (Class 0).

Undersampling worked well but reduced dataset size.

Oversampling improved recall but slightly increased false positives.

Ensemble with undersampling gave high recall for frauds but very low precision.

📌 Overall, SMOTE is the most effective technique for this dataset.

 
## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/AyaAbdelwahabAbdelhafez/Credit_Card_Fraud_Detection.git
cd Credit_Card_Fraud_Detection

---

## 👩‍💻 Author
- Aya Abdelwahab Abdelhafez
