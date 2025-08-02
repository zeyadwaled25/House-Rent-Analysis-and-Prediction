
# 🏠 House Rent Prediction

This project is a Machine Learning-based system to predict house rental prices using multiple regression models. It includes preprocessing, outlier handling, feature transformation, and model evaluation using GridSearchCV.

---

## 📌 Project Overview

The goal is to predict rent prices based on features like BHK, Size, Bathroom, and more. The dataset has been cleaned and transformed to improve prediction accuracy using several ML algorithms.

---

## 🔍 Models Used

- ✅ Linear Regression
- ✅ Support Vector Regression (SVR)
- ✅ K-Nearest Neighbors (KNN) Regression
- ✅ Decision Tree Regression
- ✅ Random Forest Regression
- ✅ Naive Bayes (Custom workaround since it's not typically used for regression)

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
📦 House-Rent-Prediction
│
├── 📂 images/
├── 📜 House_Rent_Dataset.csv
├── 📜 Rental-Price-Regression.ipynb
└── 📜 README.md
```

---

## 🧪 Model Evaluation

Each model was evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Train vs Test Score

📊 Best performing model: **Random Forest Regression**

---

## 📉 Data Preprocessing Steps

- ✅ Missing value treatment  
- ✅ Outlier removal or capping (using IQR method)  
- ✅ Encoding categorical features  
- ✅ Feature scaling (StandardScaler, MinMaxScaler, etc.)  
- ✅ SMOTE (if needed)

---

## ✨ Author

Developed by **Zeyad Waled**  
[GitHub](https://github.com/zeyadwaled25) | [LinkedIn](https://www.linkedin.com/in/zeyad-waled-3504a9295)

---

## 📌 License

This project is licensed under the MIT License.
