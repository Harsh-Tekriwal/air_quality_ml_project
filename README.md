# 🌫️ Machine Learning Based Air Quality Prediction

## 🌍 Project Overview
This project predicts air pollution levels (RSPM) and analyzes Air Quality Index (AQI) across different states in India using Machine Learning techniques.

The model uses historical pollutant data to understand patterns and evaluate air quality conditions.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing  
- Conduct Exploratory Data Analysis (EDA)  
- Train Machine Learning models  
- Evaluate and compare model performance  
- Calculate AQI and categorize pollution levels  
- Visualize state-wise AQI and India AQI map  

---

## 🛠 Tech Stack
- **Python** – Programming language  
- **Pandas & NumPy** – Data preprocessing  
- **Matplotlib** – Data visualization  
- **Plotly** – Interactive India map visualization  
- **Scikit-learn** – Machine Learning models  
- **Google Colab / Jupyter Notebook** – Execution  

---

## 🤖 Machine Learning Models Used
- **Gradient Descent (SGD Regressor)**  
- **Random Forest Regressor**

---

## 📊 Dataset
Due to size limitations, the dataset is hosted externally.

🔗 Download here:  
https://drive.google.com/file/d/1WhGcaaXoSK8GLM3t_emRGVfYOhe3EOkK/view?usp=drive_link  

📌 After downloading, place the dataset file as: data.csv
---

## 🔄 Project Workflow
1. Importing Libraries  
2. Loading Dataset  
3. Data Cleaning & Handling Missing Values  
4. Encoding Categorical Data  
5. Feature Selection  
6. Train-Test Split  
7. Feature Scaling  
8. Model Training (SGD & Random Forest)  
9. Model Evaluation (MSE & R² Score)  
10. AQI Calculation & Categorization  
11. State-wise AQI Analysis  
12. Data Visualization (Graphs & India Map)  

---

## 📈 Model Evaluation
The models are evaluated using:

- **Mean Squared Error (MSE)**  
- **R² Score**

📌 Random Forest generally performs better than Gradient Descent for this dataset.

---

## 📁 Outputs
The project generates the following outputs:

- `predictions.csv` → Model predictions  
- `metrics.txt` → Model performance (MSE & R²)  
- `state_aqi.csv` → State-wise AQI data  
- `mse.png` → MSE comparison graph  
- `r2.png` → R² comparison graph  
- `aqi_dist.png` → AQI distribution  
- `state_aqi_graph.png` → State-wise AQI visualization  
- `india_map.html` → Interactive India AQI map  

---

## 🗺️ Key Features
- AQI calculation using multiple pollutants (SO2, NO2, RSPM, SPM)  
- Categorization of AQI (Good, Moderate, Poor, etc.)  
- Visualization of pollution across Indian states  
- Interactive India AQI map  

---

## 🚀 How to Run
1. Open the notebook in Google Colab  
2. Upload the dataset (`data.csv`)  
3. Run all cells  
4. Outputs will be generated automatically  

---

## 👨‍💻 Authors
- Apurva Prasad  
- Surina Pradhan  
- Harsh Tekriwal  
- Abhishek Kumar  
- Romit Raj  
- Vineet Singh  
