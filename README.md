# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Authors

* Shahriar Hossain Rafi
* Jishan Ferdous Navil
* Munira Mubasshira Mim
* Nusrat Jahan Maria

## 🎓 Institution

American International University-Bangladesh (AIUB)
Department of Computer Science & Engineering

---

## 📖 Project Overview

This project focuses on predicting heart disease using machine learning techniques. Traditional methods often fail to capture complex patterns in medical data, so we developed an **ensemble-based model** to improve prediction accuracy.

The system analyzes patient data such as:

* Age
* BMI
* Glucose level
* Hypertension
* Smoking status
* Lifestyle factors

to determine the likelihood of heart disease.

---

## 🧠 Methodology

The project follows a complete ML pipeline:

* Data preprocessing (cleaning, encoding, scaling)
* Handling imbalance using SMOTE
* Feature reduction using PCA
* Model training and evaluation

### 🔍 Models Used

* K-Nearest Neighbors (KNN)
* Random Forest (RF)
* Gradient Boosting Classifier
* **Stacking Ensemble Model (Final Model)**

The stacking model combines KNN and RF with Gradient Boosting as a meta-learner.

---

## 📊 Results

| Model          | Accuracy   |
| -------------- | ---------- |
| KNN            | 93.78%     |
| Random Forest  | 93.62%     |
| Stacking Model | **95.32%** |

The ensemble model achieved the highest performance, proving the effectiveness of combining multiple algorithms. 

---

## 📁 Dataset

* Stroke Prediction Dataset (Kaggle)
* Includes demographic and medical features

---

## ⚙️ Technologies Used

* Python
* Scikit-learn
* Pandas, NumPy
* Matplotlib, Seaborn
* Google Colab

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/heart-disease-ml.git
cd heart-disease-ml
pip install -r requirements.txt
python main.py
```

---

## 📈 Key Features

* Ensemble learning approach for higher accuracy
* Balanced dataset using SMOTE
* PCA for dimensionality reduction
* ROC curve & confusion matrix evaluation

---

## 🔮 Future Work

* Apply deep learning models
* Use real-time hospital data
* Deploy as a web-based prediction system
* Improve interpretability for medical use

---

## 📜 License

This project is developed for academic purposes.
