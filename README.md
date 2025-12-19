# Runoff Prediction using Python, Machine Learning and Google Earth Engine

## 📌 Project Overview
This project demonstrates a simple hydrological modeling approach to predict surface runoff using satellite-based rainfall, land use, and elevation data. Google Earth Engine (GEE) is used for data extraction, and a Random Forest machine learning model is developed in Python using Google Colab.

The project is intended for educational and research purposes in water resources engineering.

---

## 🎯 Objectives
- To extract hydrological inputs using Google Earth Engine
- To prepare a dataset suitable for machine learning
- To develop a Random Forest model for runoff prediction
- To validate model results using sample-based comparison

---

## 🛠 Tools & Technologies
- Google Earth Engine (GEE)
- Python (Google Colab)
- Machine Learning (Random Forest Regressor)
- Libraries: geemap, ee, pandas, scikit-learn, matplotlib

---

## 📊 Data Used
- Rainfall: CHIRPS Daily Rainfall Dataset
- Land Use/Land Cover: ESA WorldCover
- Elevation: SRTM DEM

---

## ⚙ Methodology
1. Selection of study area (buffer-based watershed)
2. Extraction of rainfall, LULC, and DEM data using GEE
3. Conversion of satellite data to tabular format
4. Runoff estimation using a simple conceptual assumption
5. Machine learning model training and testing
6. Model validation using sample comparison and error metrics

---

## 📈 Model Validation
- Train-test data split (80%–20%)
- R² score and Mean Absolute Error (MAE)
- Sample-wise comparison of actual and predicted runoff

---

## ⚠ Limitations
- Runoff values are assumed for demonstration
- No observed discharge data used
- Simplified watershed representation

---

## 🔮 Future Improvements
- Use observed streamflow data
- Integrate SCS-CN method
- Time-series modeling using LSTM
- Sub-basin level analysis

---

## 👤 Author
Harshit Madival  
Postgraduate Student – Water Resources Engineering and Management

---

## 📜 License
This project is for academic and learning purposes.
