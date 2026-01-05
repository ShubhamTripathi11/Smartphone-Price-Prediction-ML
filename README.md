# 📱 Smartphone Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **price of smartphones** based on their hardware and technical specifications using **machine learning techniques**. It demonstrates an end-to-end **Data Science workflow**, including data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

The goal is to help understand how different smartphone features (RAM, storage, battery, camera, etc.) influence pricing and to build a predictive model that can estimate prices accurately.

---

## 🚀 Key Features

* End-to-end Machine Learning pipeline
* Exploratory Data Analysis (EDA) with visual insights
* Data preprocessing and feature engineering
* Multiple regression models for price prediction
* Model performance evaluation and comparison
* Clean, modular, and beginner-friendly implementation

---

## 🛠️ Technologies & Tools Used

* **Programming Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn
* **IDE / Environment:** Jupyter Notebook

---

## 📂 Project Structure

```
Smartphone-Price-Prediction-ML/
│
├── datasets/
│   ├── cellphones_data.csv
│   ├── cellphones_ratings.csv
│   └── cellphone_users.csv
│
├── SmartPhone_PricePrediction.ipynb   # Complete EDA + ML implementation
├── README.md                          # Project documentation
```

```
Smartphone-Price-Prediction-ML/
│
├── SmartPhone_PricePrediction.ipynb   # Main notebook with full implementation
├── README.md                          # Project documentation
```

---

## 📊 Dataset Information

This project uses **multiple real-world smartphone datasets** to build a robust price prediction model:

### 📁 Datasets Used

* **`cellphones_data.csv`**
  Contains core smartphone specifications such as brand, RAM, storage, battery capacity, processor details, and price.

* **`cellphones_ratings.csv`**
  Includes user ratings and review-based metrics that help capture market perception and popularity of devices.

* **`cellphone_users.csv`**
  Provides user-related or usage-based information that adds additional context to smartphone demand and pricing.

### 🎯 Target Variable

* **Smartphone Price**

The datasets are merged and preprocessed to perform data cleaning, feature selection, and feature engineering.

*(All datasets are used strictly for educational and learning purposes.)*

* The dataset contains smartphone specifications such as:

  * RAM
  * Internal Storage
  * Battery Capacity
  * Camera Features
  * Processor Information
* Target variable: **Smartphone Price**

*(Dataset is used for educational and learning purposes.)*

---

## 🔍 Exploratory Data Analysis (EDA)

* Distribution analysis of smartphone prices
* Correlation between features and price
* Handling missing values and outliers
* Feature importance insights

---

## 🤖 Machine Learning Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor *(if applicable)*

Model performance is evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

## 📈 Results

* The model successfully learns pricing patterns based on specifications
* Feature importance shows strong influence of RAM, storage, and battery capacity on price
* Achieves reliable prediction accuracy on test data

---

## 📌 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Smartphone-Price-Prediction-ML.git
```

2. Navigate to the project directory:

```bash
cd Smartphone-Price-Prediction-ML
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `SmartPhone_PricePrediction.ipynb`

---

## 📌 Future Improvements

* Deploy the model using **Streamlit or Flask**
* Add more advanced models (XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Include real-time smartphone data
* Convert notebook into a modular Python package

---

## 👨‍💻 Author

**Shubham Tripathi**
MCA (Data Science) | Aspiring Data Scientist

---

## ⭐ If you found this project helpful

Give this repository a ⭐ and feel free to fork or contribute!
