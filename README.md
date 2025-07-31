## 🧠 Breast Cancer Prediction Using Logistic Regression

### 📌 Project Description

This project demonstrates how to use **Logistic Regression** to classify breast cancer tumors as **malignant** or **benign** based on diagnostic measurements. It uses the **Breast Cancer Wisconsin dataset** from **scikit-learn**, a built-in and widely used dataset for binary classification.

---

### 💻 Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

---

### 🚀 Project Workflow

#### 1. **Data Collection and Loading**

* Load the Breast Cancer dataset using `sklearn.datasets.load_breast_cancer()`.
* Convert the data into a Pandas DataFrame with readable column names.

#### 2. **Exploratory Data Analysis (EDA)**

* View dataset structure using `.head()`, `.info()`, `.describe()`, and `.shape`.
* Check for missing values and analyze target variable distribution.

#### 3. **Data Preprocessing**

* Split the dataset into **features (X)** and **labels (Y)**.
* Prepare data for training and testing using `train_test_split()`.

#### 4. **Model Training**

* Train a **Logistic Regression** model using scikit-learn.
* Adjusted for large iterations (`max_iter=10000`) for convergence.

#### 5. **Model Evaluation**

* Evaluate the model using **accuracy\_score** on both training and testing datasets.

#### 6. **Building a Predictive System**

* Accepts a tuple of values as input.
* Predicts whether the cancer is **malignant** or **benign** based on the input.

---

### ✅ Sample Prediction Output

```python
🔮 Predictive System Result:
🟢 The Breast Cancer is Benign
```

---

### 📊 Results

| Metric            | Value     |
| ----------------- | --------- |
| Training Accuracy | \~98–100% |
| Testing Accuracy  | \~95–97%  |

---

### 📁 Folder Structure

```
Breast-Cancer-Prediction/
│
├── Breast_Cancer_LogisticRegression.ipynb   # Jupyter Notebook or Colab file
├── README.md                                # Project documentation
```

---

### 🧪 Testing

* The model is trained on historical diagnostic data.
* You can provide new data to the predictive system as a tuple to test outcomes.

---


