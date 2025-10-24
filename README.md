# 💻 Capstone Project 2: Laptop Price Prediction using Machine Learning (Python) & Power BI  

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-yellow?logo=power-bi)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Modeling-green?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

![](img1.jpg)

---
---

## 📘 Overview  
This project focuses on predicting **laptop prices** using **Machine Learning** techniques in **Python**, complemented by an **interactive Power BI dashboard** for insightful visual analysis.  

The objective is to build a predictive model capable of estimating laptop prices based on technical specifications such as Company, model type, Inches, ScreenResolution, Cpu, Ram, Memory, Gpu, OpSys, Weight, Price  
The project concludes with a business-ready Power BI dashboard and presentation summarizing key findings.  

---

## 📊 Dataset  
- **Source:** Publicly available dataset (e.g., Kaggle or web-scraped data).  
- **Description:** The dataset includes specifications of laptops with features such as:  
  - Unnamed: 0.1, Unnamed: 0, Company, model type, Inches, ScreenResolution, Cpu, Ram, Memory, Gpu, OpSys, Weight, Price( feature variable) 
  - Price (Target Variable)  

---

## 🧰 Tools & Technologies  
| Category | Tools Used |
|-----------|-------------|
| **Programming Language** | Python |
| **Libraries** | pandas, numpy, matplotlib, seaborn, scikit-learn |
| **Visualization** | Power BI |
| **Presentation** | Microsoft PowerPoint |
| **IDE** | colab/ Jupyter Notebook  |

---

## 🔍 Project Workflow  

### 1️⃣ Data Importing  
- Loaded the dataset using `pandas`.  
- Reviewed data structure, types, and missing values.  

### 2️⃣ Data Preprocessing  
- Handled missing values, duplicates, and outliers.  
- Encoded categorical variables.  
- Normalized numerical features for consistent scaling.
- Removed redundant or non-informative columns.  


### 4️⃣ Exploratory Data Analysis (EDA)  
- Visualized data trends and correlations.  
- Identified key variables influencing laptop prices.  
- Used heatmaps, histograms, and pairplots for pattern discovery.

### 3️⃣ Feature Selection
- Selecting relevent feature columns for modelling
- Log transformed Price column used

### 5️⃣ Model Development  
- Split data into training and test sets.  
- Implemented models including **Linear Regression**, **Random Forest**, and **XGBoost**.  
- Evaluated models using metrics like **RMSE**, **R²**, and **MAE**.  

### 6️⃣ Hyperparameter Tuning  
- Used **RandomizedSearchCV** for model optimization.  
- Selected the best-performing model for final deployment.  

### 7️⃣ Real-Time Predictions  
- Built a interactive prediction function to estimate laptop prices from user input.  

### 8️⃣ Power BI Dashboard  
- Imported cleaned dataset into Power BI.  
- Designed interactive visuals and filters for:  
  -  Overview
  - Most preffered features
  - Model performance
- Developed an executive summary for business stakeholders. (Overview)

---

## 📈 Results & Insights  
- Achieved accurate laptop price predictions with a robust model.  
- Identified **top predictors**: RAM, Screen Resolution (X_res, Y_res), and SSD capacity.  
- Created a **dynamic Power BI dashboard** showcasing data trends and KPIs.  
- Compiled results and visuals into a **Capstone_project2_ppt pdf**.  

---

## 📊 Power BI Dashboard Preview   
![Dashboard Screenshot](dashboard1.jpg)
![Dashboard Screenshot](dashboard2.jpg)
![Dashboard Screenshot](dashboard3.jpg)
---

