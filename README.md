# Linear-Regression-on-education-dataset
A minimal and educational implementation of linear regression to explore how study hours influence student test scores. Ideal for ML beginners practicing supervised learning.

# 📘 Simple Linear Regression - Education Domain

This project applies **Simple Linear Regression** to predict student **test scores** based on the number of **study hours**. It demonstrates how machine learning can be used to model and visualize the relationship between two educational variables.

---

## 📊 Dataset Overview

The dataset contains two columns:
- `Study_Hours`: Number of hours the student studied
- `Test_Score`: Marks obtained in the test

---

## 🎯 Project Objective

To train a **Simple Linear Regression model** that estimates a student’s test score from their study hours. This is a classic regression problem used widely for educational purposes.

---

## 🧪 Tools and Libraries Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🛠️ Steps Performed

1. **Importing Dataset**
2. **Exploratory Data Analysis**
   - Scatter plot
   - Correlation check
3. **Model Building**
   - Linear regression using `sklearn.linear_model`
   - Model fitting
4. **Model Evaluation**
   - R² score
   - Prediction vs actual values plot

---

## 📁 Project Structure

├── simple_reg_education_dataset.ipynb # Jupyter Notebook with full implementation
├── education_study_vs_score.csv # Cleaned CSV dataset
└── README.md # Project documentation


---

## 📈 Output

The final model draws a best-fit line and makes predictions based on the number of hours studied. The graph shows how increased study time generally leads to higher scores.

---

## 👤 Author

**Ankita Pawar**

---

## 💡 Future Ideas

- Add more features (e.g., attendance, sleep hours)
- Try polynomial regression
- Apply on real academic performance datasets
