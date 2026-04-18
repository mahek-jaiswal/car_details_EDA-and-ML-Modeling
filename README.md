# 🚗 Car Price Category Prediction (Machine Learning Project)

## 📌 Project Overview
This project focuses on predicting the **price category of cars** using machine learning techniques.  
It involves **data cleaning, exploratory data analysis (EDA), feature engineering, and model building**.

The dataset contains various features such as fuel type, transmission, seller type, kilometers driven, etc., which are used to classify cars into different price categories.

---

## 🎯 Objectives
- Perform **data cleaning and preprocessing**
- Handle missing values using real-world techniques
- Perform **Exploratory Data Analysis (EDA)**
- Encode categorical features
- Scale numerical data
- Train a machine learning model to predict car price category

---

## 📂 Project Structure

├── car_details_EDA.ipynb # Data Cleaning & Exploratory Data Analysis
├── car_details_ml_model.ipynb # Model Building & Evaluation
├── dataset.csv # Dataset (not included / optional)
└── README.md # Project Documentation


---

## 📊 Dataset Description
The dataset contains the following key features:

- `selling_price` – Price of the car
- `km_driven` – Distance driven
- `fuel` – Fuel type (Petrol/Diesel/CNG)
- `seller_type` – Individual/Dealer
- `transmission` – Manual/Automatic
- `owner_count` – Number of previous owners
- `brand` – Car brand
- `price_category` – Target variable

---

## 🔍 Exploratory Data Analysis (EDA)
Performed using:
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**

### Key Steps:
- Handling missing values
- Filling missing values using:
  - Mean / Median
  - Mode
  - Custom logic
- Data distribution analysis
- Outlier understanding

---

## 🧹 Data Preprocessing
- Dropped unnecessary columns (`vehicle_uid`, `name`)
- Label Encoding applied on categorical columns:
  - fuel
  - seller_type
  - transmission
  - owner
  - brand
- Standard Scaling applied on numerical features

---

## 🤖 Machine Learning Model
- Problem Type: **Classification**
- Target Variable: `price_category`

### Steps:
- Feature selection (X) and target (y)
- Encoding categorical variables
- Feature scaling using **StandardScaler**
- Model training (Decision Tree / others if used)

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Output
- Predicts the **price category** of a car based on input features
- Helps in understanding car pricing patterns

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn
Run notebooks:
Open car_details_EDA.ipynb
Open car_details_ml_model.ipynb
📌 Future Improvements
Try advanced models (Random Forest, XGBoost)
Hyperparameter tuning
Deploy model using Flask/Django
Build a web interface
🙌 Acknowledgement

This project was developed as part of a Machine Learning / Data Science academic project.# car_details_EDA-and-ML-Modeling
