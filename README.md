# 🧮 Price Predictor — Universal ML Template
### **ML for everyone — right inside a spreadsheet.**

💭 *“What’s a fair price of a laptop, car, phone, house, or insurance premium?”*  
This project answers that question using a **generic, reusable, no-code ML engine** built for *any* dataset.

---

## 🚀 Overview

Instead of creating a one-off machine learning model, this project delivers a **configurable ML template** that works across **any product category**.  
Upload a dataset → It automatically prepares data → Trains 2 models → Provides insights → Predicts price.

A fully automated pipeline — **no coding needed**.

---

## ✨ What This ML Template Does

### 🔍 **Automatic Data Understanding**
- Detects the **target column** (e.g., `price`, `value`, `cost`)
- Splits columns into **numerical** and **categorical**
- Identifies missing values
- Optional outlier removal or capping

### ⚙️ **End-to-End Pipeline**
- Cleans + transforms data
- Encodes categorical features
- Scales numerical features
- Trains **Random Forest** & **Linear Regression**
- Compares performance using:
  - **MAE**
  - **R² Score**

### 📊 **Insights**
- Generates a **Plotly bar chart** of top features
- Shows model error comparison
- Displays feature importance for Random Forest

### 💵 **Live Price Prediction**
Enter new values → Instantly get predicted price  
Feels like a spreadsheet, behaves like a data scientist.

---

## 🌟 Who This Is For

| User Type | Why It Helps |
|----------|---------------|
| **Everyday Users** | Estimate price of products before buying/selling |
| **Students** | Learn real-world ML workflows without coding |
| **Data Analysts** | Rapid prototyping on any dataset |
| **Business Owners** | Estimate inventory / product price ranges |
| **ML Beginners** | Understand end-to-end ML without complex code |

---

## 🧰 Use Cases

This template is reusable for:
- 💻 Laptop price prediction  
- 🚗 Car valuation  
- 📱 Mobile phone pricing  
- 🏡 Real estate price estimation  
- 🛡️ Insurance premium prediction  
- 📦 Ecommerce product pricing  
- 🧾 Financial / cost estimation tasks  

---

## Template Link:

[Template](https://app.quadratichq.com/file/1f45742b-099c-447d-b933-eeb82f5d6d55)

## ✅ Steps to Use the Price Prediction Template		
1. In the Data sheet, upload your dataset as a CSV file.		
🔸 File name must be exactly: data.csv		
		
2. Switch to the Prediction sheet, and		
press Ctrl + Enter in the Python cells to rerun the model training and prediction pipeline.		
		
3. To predict a new laptop's price: (by default last row is taken as sample input for price prediction		
➕ Append a new row at the bottom of your dataset with input features filled in.		
🔹 Leave the price field blank — it will be predicted.		
		
4. The code will automatically:		
Detect the last row as the new input.		
Display the input features.		
Show the predicted price.

## Sample Data
Sample data has been provided in this repo under 5 folders.
Use them and explore!
