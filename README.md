# 🌼 Iris Flower Classification — Machine Learning Project

A simple end-to-end **Machine Learning** project built in **Google Colab** using the classic **Iris dataset** 🌸  
The goal is to predict the species of an Iris flower based on its petal and sepal measurements.

---

## 🧠 Overview
- **Problem Type:** Multi-class classification (3 species)
- **Models Used:** Logistic Regression, Random Forest
- **Tools:** Python, pandas, seaborn, scikit-learn, matplotlib

---

## 📊 Steps
1. **Data Loading:** Imported the Iris dataset from `sklearn.datasets`.
2. **EDA:** Explored data distributions, created pairplots and boxplots to understand feature importance.
3. **Modeling:**  
   - Trained **Logistic Regression** and **Random Forest** models.  
   - Evaluated using accuracy, confusion matrix, and classification report.
4. **Comparison:** Visualized model performance using a simple Seaborn bar plot.

---

## 📈 Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **97%** |
| Random Forest | **93%** |

- **Petal length** and **petal width** are the most important features.
- Logistic Regression performed slightly better since the dataset is small and nearly linearly separable.

---

## 🧩 Files in this Repository
- `iris_flower_ml.ipynb` — Google Colab notebook with full code & outputs  
- `README.md` — Project summary and documentation  

---

## 💡 Key Learnings
- Performing EDA to discover useful features  
- Training and evaluating multiple ML models  
- Understanding why simpler models can outperform complex ones  

---

Built with ❤️ in Google Colab.
