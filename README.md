
# 📱 Cellphone Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting mobile phone price ranges based on technical specifications using Machine Learning algorithms.

## 🎯 Problem Statement

Predict the mobile phone price category using specifications such as RAM, battery power, screen resolution, internal memory, and other features.

| Price Range | Category |
|:---:|---|
| 0 | Low Cost |
| 1 | Medium Cost |
| 2 | High Cost |
| 3 | Very High Cost |

## 📂 Dataset Information

- 📊 Total Records: 2,000
- 🔢 Input Features: 20
- 🎯 Target Variable: `price_range`
- 🤖 Problem Type: Multi-class Classification

## 🛠️ Technologies & Libraries

- 🐍 Python
- 🧮 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

## 🔍 Exploratory Data Analysis

- 📈 Univariate Analysis
- 🔗 Bivariate Analysis
- 📊 Multivariate Analysis
- 📉 Distribution Analysis
- 🔎 Outlier Detection
- 🔥 Correlation Analysis

## ⚙️ Data Preprocessing

- ✅ Checked missing values and duplicates.
- ✅ Identified zero values in selected features.
- ✅ Removed two records with zero `px_height`.
- ✅ Handled zero values in `sc_w` using the training data median.
- ✅ Performed an 80:20 train-test split.
- ✅ Applied StandardScaler to Logistic Regression, KNN, and SVM.

## 🤖 Machine Learning Models

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. Naive Bayes

## 📊 Model Performance

| Model | Testing Accuracy |
|---|---:|
| 🥇 Logistic Regression | **95.8%** |
| 🌳 Random Forest | 88.2% |
| ⚡ SVM | 87.5% |
| 📘 Naive Bayes | 81.5% |
| 🌲 Decision Tree | 79.5% |
| 📍 KNN | 53.5% |

## ⭐ Feature Importance

Top features based on Logistic Regression coefficient analysis:

- 🥇 RAM
- 🔋 Battery Power
- 🖥️ Pixel Width
- 📱 Pixel Height
- ⚖️ Mobile Weight

## 💡 Business Recommendations

- 📱 Focus on RAM when designing mobile price segments.
- 🔋 Consider battery capacity for product differentiation.
- 🖥️ Consider screen resolution when positioning products.
- 💰 Use price categories to support product planning.
- 📈 Apply Machine Learning to support data-driven pricing decisions.

## 🏆 Final Conclusion

Logistic Regression achieved the highest testing accuracy of **95.8%** among the six evaluated models and was selected as the best-performing model.

RAM was identified as the most influential feature in the model's coefficient analysis.

## 📁 Project Structure

```text
Cellphone-Price-Prediction/
│
├── PRCP-1009 Cellphone Price Prediction.ipynb
├── Cellphone_Price_Prediction_Project_Report.docx
└── README.md
```

## 👨‍💻 Author

**Subham kumar shaw**

🎓 Data Science | Aspiring Data Analyst / Data Scientist

🔗 GitHub: [SKKUMARSHAW](https://github.com/SKKUMARSHAW)

---

⭐ If you find this project useful, feel free to explore the notebook and share your feedback!
