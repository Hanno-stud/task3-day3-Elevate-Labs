# 🏠 Task 3: Housing Price Prediction using Linear Regression

## 📌 Objective
To build and evaluate a **Linear Regression Model** to predict housing prices based on multiple features from the Housing dataset.  
This task demonstrates the full machine learning pipeline from **data preprocessing** to **model evaluation and visualization.**

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – Data handling & preprocessing
- **Seaborn** – Statistical visualizations
- **Matplotlib** – Basic plotting
- **Scikit-Learn** – Linear Regression, train-test split, evaluation metrics

---

## 📂 Dataset Description
The dataset (`Housing.csv`) contains various features related to houses and their prices, including:
- **Price** (target variable)
- **Area** (square feet)
- **Bedrooms**, **Bathrooms**, **Stories**
- **Mainroad**, **Guestroom**, **Basement**, **Hotwaterheating**, **Airconditioning**, **Prefarea** – categorical features
- **Furnishingstatus** – categorical feature

All **categorical columns are encoded** using one-hot encoding.  
The dataset is **clean and does not contain null values.**

---

## 🔍 Key Steps in the Project

### 1️⃣ Dataset Import and Preprocessing
- Loaded the housing dataset using Pandas.
- Applied **one-hot encoding** to categorical features using `get_dummies()`.
- Dropped the first category to avoid multicollinearity.

### 2️⃣ Train-Test Split
- Split the dataset into **80% training** and **20% testing** using `train_test_split`.

### 3️⃣ Model Building
- Fitted a **Linear Regression Model** using `sklearn.linear_model.LinearRegression`.

### 4️⃣ Model Evaluation
- Evaluated using:
    - **MAE (Mean Absolute Error)**
    - **MSE (Mean Squared Error)**
    - **R² (Coefficient of Determination)**
- Printed **model coefficients and intercept** for interpretability.

### 5️⃣ Visualizations
- **Actual vs. Predicted Prices Plot** (Multivariable Regression)
- **Simple Linear Regression Plot (Area vs. Price)** to demonstrate a regression line.
- **Correlation Heatmap** to explore feature relationships.

---

## 📈 Key Outputs

![image](https://github.com/user-attachments/assets/bbeef062-df87-4a27-874d-32ece779efa6)

![image](https://github.com/user-attachments/assets/c6544115-7edd-4d7d-97a4-38f6ecaa59dc)

- Model coefficients are displayed in tabular form for each feature.

---

## 🧠 Insights & Interpretations
- Coefficients explain **how much each feature influences the house price.**
- Some features (like area, air conditioning, and furnishing status) have a **higher impact on pricing.**
- The **regression line for Area vs. Price** shows a positive correlation.
- The **correlation heatmap** reveals multicollinearity between some engineered features.

---

## 📁 Files Included
- `Housing.csv` – Dataset
- `LinearRegression.ipynb` – Jupyter Notebook
- `LinearRegression.py` – Python source file
- `README.md` – This documentation file

---

## 🚀 Next Steps
- Improve the model by adding **feature scaling** or **interaction terms.**
- Try **polynomial regression** to capture non-linear relationships.
- Perform **residual analysis** for deeper error investigation.

---

## 📸 Outputs
![image](https://github.com/user-attachments/assets/9937aea3-1cea-4701-b716-7a3f0e414d5a)
<br/>
![image](https://github.com/user-attachments/assets/a41d2023-88c5-40cb-b81f-bb6daa5ecdb2)
<br/>
![image](https://github.com/user-attachments/assets/7fb02505-2b35-4bcc-9c6f-a31a4cae55cf)

---

