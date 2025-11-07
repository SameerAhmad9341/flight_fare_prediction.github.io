# flight_fare_prediction.github.io
# ✈️ Flight Fare Prediction

## 📘 Project Overview
The **Flight Fare Prediction** project aims to forecast flight ticket prices based on multiple travel parameters such as airline, source, destination, journey date, duration, and number of stops. By analyzing historical flight data, the project helps users and travel agencies estimate ticket costs and plan trips efficiently.

## 🎯 Objective
To build a machine learning model that accurately predicts flight fares using various flight and journey-related features.

## 🧩 Dataset Description
The dataset (`Flight_Fare.xlsx`) includes the following key features:
- **Airline** – Type of airline (e.g., Indigo, Jet Airways, Air India)
- **Date_of_Journey** – Date when the flight departs
- **Source** – City of departure
- **Destination** – Arrival city
- **Route** – Path taken by the flight
- **Dep_Time / Arrival_Time** – Departure and arrival timings
- **Duration** – Total travel duration
- **Total_Stops** – Number of stops between source and destination
- **Additional_Info** – Miscellaneous flight details (e.g., meal, baggage)
- **Price** – Target variable representing flight fare

## ⚙️ Project Workflow
1. **Data Loading** – Import dataset and perform initial exploration.  
2. **Data Preprocessing** – Handle missing values, clean text, and convert date/time columns.  
3. **Feature Engineering** – Extract day, month, and duration information; encode categorical variables.  
4. **Model Training** – Apply regression models like:
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
5. **Model Evaluation** – Evaluate performance using metrics such as RMSE and R² score.  

## 🧠 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 📊 Results
The final model accurately predicts flight fares based on the provided parameters, supporting smarter ticket booking and pricing strategies.

## 🚀 Future Enhancements
- Include real-time flight API data.  
- Implement deep learning regression for higher accuracy.  
- Deploy model as a web app using Flask or Streamlit.

---

📁 **Author:** *Your Name*  
📅 **Project:** Flight Fare Prediction  
