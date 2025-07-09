# 🌾 Crop Disease Management System

A comprehensive **database-driven system** designed to manage crop diseases, irrigation, pesticides, and yield prediction. The project uses **MySQL** to organize and query agricultural data, with stored procedures for disease alerts, pesticide recommendations, and yield forecasting.

---

## 📌 Project Overview

🚜 **Agricultural Challenge:**
- Crop diseases are a major cause of yield loss globally.
- Lack of timely insights and poor pesticide management hampers farm productivity.
- Weather plays a crucial role in disease outbreaks and irrigation needs.

🎯 **System Objectives:**
- Track and monitor crop health.
- Predict diseases based on environmental data.
- Recommend pesticides and optimize irrigation.
- Improve yield predictions using historical data.

---

## 🧠 What I Learned

✅ Designed a normalized relational database schema using **ER modeling and 3NF** principles.  
✅ Implemented **complex relationship sets** (1:1, 1:M, M:N) with constraints.  
✅ Created **stored procedures** for:
  - Disease alerts based on environmental and crop data.
  - Yield prediction models using weather and irrigation history.
  - Pesticide recommendations based on disease diagnosis.

✅ Gained hands-on experience in:
- Relational database design and normalization.
- Writing efficient **MySQL queries and procedures**.
- Converting client requirements into database logic.
- Visual presentation via **ER diagrams and system overviews**.

---

## 🗂️ Features

### 🌱 Crop Management
- Store crop types, planting dates, resistance levels, and yield estimates.
- Manage crop growth stages and related diseases.

### 🦠 Disease Monitoring
- Track diseases, symptoms, severity, and treatments.
- Identify diseases based on weather and crop input.

### 💧 Irrigation Scheduling
- Optimize watering schedules based on crop type and weather data.

### 🧪 Pesticide Management
- Store pesticide information, dosage, and approved crops.
- Recommend suitable pesticides based on diagnosed diseases.

### ☁️ Weather Integration
- Collect temperature, rainfall, humidity, and wind data.
- Correlate environmental patterns with disease outbreaks.

### 📊 Yield Prediction
- Forecast yield using irrigation and disease history.
- Improve planning and resource allocation.

---

## 🛠️ Database Design

- Fully normalized schema (up to **3NF**).
- Relationships include:
  - Crop ⟷ Disease (Many-to-Many)
  - Crop ⟶ Pesticide (Many-to-One)
  - Disease ⟶ WeatherData (Many-to-One)
  - Crop ⟷ IrrigationSchedule (1:1)
  - Irrigation ⟶ Yield (One-to-Many)

---

## 📈 Stored Procedures

1. **Disease Alert**  
   Returns likely diseases for a crop based on temperature, humidity, and weather.

2. **Yield Prediction**  
   Predicts expected yield using crop type, weather, and disease conditions.

3. **Pesticide Recommendation**  
   Suggests pesticides based on the diagnosed disease.

---

## 📦 Folder Structure

---

## 🖼️ Visuals

### 📌 System Overview  
![System Overview](diagrams/overview.png)

### 🌿 Crop Lifecycle  
![Crop Lifecycle](diagrams/crop_lifecycle.png)

### 📊 ER Diagram  
![ER Diagram](/ERD SQL.png)

---

## 📚 Client Requirements Summary

- Track diseases and symptoms per crop.
- Collect and analyze weather data for disease prediction.
- Store detailed pesticide usage data.
- Maintain crop growth and yield records.
- Implement normalized relational schema and enforce data consistency.

---

## 🚀 Future Enhancements

- Integration with real-time weather APIs.
- Web dashboard for farmers to query diseases and get alerts.
- Mobile app support for field data entry.
- AI-based yield forecasting using ML models.

---

## 🧑‍💻 Author

**Dinesh Kumar Raju Kattunga**  
[LinkedIn](https://linkedin.com/in/dineshkumarraju0223/) | [GitHub](https://github.com/dineshraju147)

---

## 📜 License

This project is licensed under the MIT License.

