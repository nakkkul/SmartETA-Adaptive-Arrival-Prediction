# 🏙️ Dynamic ETA Prediction System

### 📜 Overview  
The **Dynamic ETA Prediction System** is designed to estimate the Estimated Time of Arrival (ETA) across city routes using a data-driven approach. The project simulates real-world traffic conditions by leveraging **OpenStreetMaps data** and incorporating factors like **route complexity, traffic flow, and time of day**. The system provides dynamic ETA predictions, continuously updating as new route data becomes available.  

This project aims to enhance real-time navigation and logistics planning by making ETA calculations more adaptive and precise.  

---

### 🎯 Key Features  
✅ **Dynamic ETA Adjustments** – Predictions update as new route conditions emerge.  
✅ **Segment-Level Analysis** – Estimates vary across different sections of the journey.  
✅ **Data-Driven Approach** – Uses simulated traffic and route complexity variables.  
✅ **Multiple Model Comparisons** – Evaluates different regression techniques for accuracy.  

---

### 🏗️ Model Development  
Two machine learning models were trained and tested for ETA prediction:  

1️⃣ **Decision Tree Regressor**  
2️⃣ **Random Forest Regressor**  

Both models were evaluated using key regression metrics, including:  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  

After comparison, the **Random Forest Regressor** demonstrated superior performance by effectively capturing complex and non-linear relationships in the dataset, making it the preferred model for ETA prediction.  

---

### 🚀 Future Enhancements  
🔹 **Hyperparameter Optimization** – Fine-tune Random Forest parameters (e.g., number of trees, depth) to improve accuracy.  
🔹 **Feature Engineering** – Explore additional factors like weather conditions, real-time traffic updates, and road closures.  
🔹 **Scalability** – Adapt the model for real-world applications, integrating live traffic feeds for continuous predictions.  

---

### 🏆 Conclusion  
The **Random Forest Regressor** has proven to be the most effective model for predicting ETA in this simulated environment, outperforming the Decision Tree Regressor. The project’s focus on **distance, current speed, and historical speed** as primary predictive features played a crucial role in achieving accurate results.  

Further enhancements will refine the system, making it highly applicable to **real-world navigation, ride-sharing platforms, and logistics management** where precise ETA calculations are critical.  
