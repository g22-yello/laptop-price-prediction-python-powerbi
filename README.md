# Laptop_price_prediction-using-ML-with-Python-Power-BI
Capstone DS project: Predict laptop prices using Machine Learning with Python and visualize insights with Power BI. Includes data preprocessing, EDA, feature engineering, model training (Linear Regression, Random Forest, Gradient Boosting), hyperparameter tuning, and interactive interface, Business Insights and dashboard

# 💻 Capstone Project 2: Laptop Price Prediction using Machine Learning (Python) & Power BI  

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-yellow?logo=power-bi)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Modeling-green?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📘 Overview  
This project focuses on predicting **laptop prices** using **Machine Learning** techniques in **Python**, complemented by an **interactive Power BI dashboard** for insightful visual analysis.  

The objective is to build a predictive model capable of estimating laptop prices based on technical specifications such as brand, processor, RAM, storage, GPU, and display.  
The project concludes with a business-ready Power BI dashboard and presentation summarizing key findings.  

---

## 📊 Dataset  
- **Source:** Publicly available dataset (e.g., Kaggle or web-scraped data).  
- **Description:** The dataset includes specifications of laptops with features such as:  
  - Brand / Company  
  - Type Name  
  - RAM  
  - Storage (HDD / SSD)  
  - GPU  
  - CPU  
  - Screen Size & Resolution  
  - Operating System  
  - Price (Target Variable)  

---

## 🧰 Tools & Technologies  
| Category | Tools Used |
|-----------|-------------|
| **Programming Language** | Python |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost |
| **Visualization** | Power BI |
| **Presentation** | Microsoft PowerPoint |
| **IDE** | Jupyter Notebook / VS Code |

---

## 🔍 Project Workflow  

### 1️⃣ Data Importing  
- Loaded the dataset using `pandas`.  
- Reviewed data structure, types, and missing values.  

### 2️⃣ Data Preprocessing  
- Handled missing values, duplicates, and outliers.  
- Encoded categorical variables.  
- Normalized numerical features for consistent scaling.  

### 3️⃣ Feature Engineering  
- Derived new insights from existing columns (e.g., pixel density, storage type).  
- Removed redundant or non-informative columns.  

### 4️⃣ Exploratory Data Analysis (EDA)  
- Visualized data trends and correlations.  
- Identified key variables influencing laptop prices.  
- Used heatmaps, histograms, and pairplots for pattern discovery.  

### 5️⃣ Model Development  
- Split data into training and test sets.  
- Implemented models including **Linear Regression**, **Random Forest**, and **XGBoost**.  
- Evaluated models using metrics like **RMSE**, **R²**, and **MAE**.  

### 6️⃣ Hyperparameter Tuning  
- Used **GridSearchCV** for model optimization.  
- Selected the best-performing model for final deployment.  

### 7️⃣ Real-Time Predictions  
- Built a prediction function to estimate laptop prices from user input.  

### 8️⃣ Power BI Dashboard  
- Imported cleaned dataset into Power BI.  
- Designed interactive visuals and filters for:  
  - Average price by brand  
  - Price trends by RAM, CPU, GPU  
  - Price distribution by storage type or OS  
- Developed an executive summary for business stakeholders.  

---

## 📈 Results & Insights  
- Achieved accurate laptop price predictions with a robust model.  
- Identified **top predictors**: RAM, Processor Type, GPU, and Storage.  
- Created a **dynamic Power BI dashboard** showcasing data trends and KPIs.  
- Compiled results and visuals into a **final PowerPoint presentation**.  

---

## 📊 Power BI Dashboard Preview  
> *(Add your screenshot here once ready)*  
![Dashboard Screenshot](images/powerbi_dashboard.png)

---

## ▶️ How to Run  

### 1. Clone the Repository  
```bash
git clone https://github.com/yourusername/Capstone_project2_Laptop_price_prediction-using-ML-with-Python-PowerBI.git
cd Capstone_project2_Laptop_price_prediction-using-ML-with-Python-PowerBI
