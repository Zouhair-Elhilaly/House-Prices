# House-Prices
Machine Learning Project for predict PriceSales for house



---

# 🧠 Regression Lab – Ames Housing

## 📋 Project Overview

This project performs a complete regression analysis on the **Ames Housing dataset**.
The objective is to:

1. Load and explore the dataset.
2. Detect and handle data issues such as missing values and outliers.
3. Preprocess the data (encoding, scaling, imputing).
4. Train and evaluate three regression models:

   * **Linear Regression**
   * **Lasso Regression**
   * **Ridge Regression**
5. Compare model performance and interpret the results.

---

## ⚙️ Environment Setup

### Python Version

* **Python 3.13.6**

### Required Libraries and Versions

| Library      | Version |
| ------------ | ------- |
| Numpy        | 2.3.2   |
| Pandas       | 2.3.2   |
| Scikit-learn | 1.7.2   |
| Matplotlib   | 3.10.5  |
| Seaborn      | 0.3.12  |

---

## 🧩 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Zouhair-Elhilaly/House-Prices.git
   cd House-Prices
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the environment:**

   * On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```
   * On Windows:

     ```bash
     venv\Scripts\activate
     ```

4. **Install dependencies:**

   ```bash
   pip install numpy==2.3.2 pandas==2.3.2 scikit-learn==1.7.2 matplotlib==3.10.5 seaborn==0.3.12
   ```

---

## 📊 Project Structure

```
Regression-Lab/
│
├── AmesHousing.csv           # Dataset 
├── README.md                # Project documentation
└── Tp2_regression.ipynb      # Main analysis notebook
```

---

## 🚀 How to Run

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook notebooks/House-Prices.ipynb
   ```
2. Follow the exercises in order:

   * Data loading and exploration
   * Preprocessing
   * Model training and evaluation
   * Model comparison and summary

---

## 📈 Models Evaluated

* **Linear Regression**
* **Lasso Regression**
* **Ridge Regression**

Metrics used:

* **Mean Squared Error (MSE)**
* **R² Score**

---

## 🧠 Key Learnings

* Handling missing data effectively.
* Understanding correlations among features.
* Applying regularization techniques (Lasso, Ridge).
* Comparing and interpreting model performance.

---

## 💡 Next Steps

* Apply log-transformation on the target.
* Perform cross-validation and hyperparameter tuning.
* Add pipeline automation for preprocessing and training.

---
