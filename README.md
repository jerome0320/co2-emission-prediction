# 🚗 CO2 Emissions Prediction Based on Vehicle Features

## 📌 Project Overview
This project aims to predict **CO2 emissions** of vehicles using various car engine and fuel-related features. Using real-world vehicle data, we apply data science and machine learning techniques to estimate emissions and deploy the results via a web application using **Streamlit**.

---

## 🎯 Business Objective
To develop a machine learning model that can accurately **predict CO2 emissions** (g/km) based on a car's specifications such as engine size, transmission type, and fuel consumption. The objective is to help manufacturers, policymakers, and users make **data-driven decisions** for sustainability and regulatory compliance.

---

## 📂 Dataset Description

- **Rows (Instances):** 7385  
- **Columns (Features):** 12  

### ✅ Variables:
| Feature                        | Description                                  |
|-------------------------------|----------------------------------------------|
| `make`                        | Car brand                                    |
| `model`                       | Model of the car                             |
| `vehicle_class`               | Body type                                    |
| `engine_size`                 | Engine size in liters                        |
| `cylinders`                   | Number of engine cylinders                   |
| `transmission`               | Transmission type (e.g., A, M, AV, etc.)     |
| `fuel_type`                  | Fuel type (e.g., Regular, Premium, Diesel)   |
| `fuel_consumption_city`      | City mileage in L/100km                      |
| `fuel_consumption_hwy`       | Highway mileage in L/100km                   |
| `fuel_consumption_comb(l/100km)` | Combined mileage (L/100km)              |
| `fuel_consumption_comb(mpg)` | Combined mileage (mpg)                       |
| `co2_emissions`              | Target variable – CO2 emission (g/km)        |

---

## 🛠️ Tools and Technologies

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Modeling**: Linear Regression, Random Forest  
- **Deployment**: Streamlit  
- **Others**: Power BI (for additional dashboard insights)

---

## 🚀 Project Workflow

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Model Training & Evaluation**
5. **Visualization**
6. **Deployment using Streamlit**

---

## 💻 Running the Project Locally

### Prerequisites
- Python 3.8+
- Install requirements:  
```bash
pip install -r requirements.txt
