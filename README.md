# 🌍 Earthquake Prediction Using Linear Regression

## 📄 Project Overview
This project aims to predict earthquake magnitudes using a linear regression model. The dataset includes records of recent earthquakes with features like magnitude, location, depth, and timestamp. By analyzing these factors, we assess how well magnitudes can be predicted based on other attributes.



## 📊 Dataset
- **Name:** Recent Earthquakes Dataset  
- **Source:** [Kaggle](https://www.kaggle.com)  
- **Description:** Contains 1,137 records of global seismic activity with the following attributes:  
  - 🗓 **Date & Time:** Timestamp of the earthquake occurrence.  
  - 📍 **Latitude & Longitude:** Geographic coordinates of the epicenter.  
  - 🌐 **Depth:** Depth of the earthquake (in kilometers).  
  - 🌡 **Magnitude:** Richter scale value.  
  - 🗺 **Location:** General description (e.g., nearby cities).  



## 🎯 Objective
Develop a **linear regression model** to predict earthquake magnitudes based on other dataset features.



## 🛠 Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- 🔄 **Correlation Matrix:**  
  - Positive correlation observed between tsunami significance (`sig`) and magnitude.  
  - Negative correlation noted between depth and latitude.  
- 📈 **Scatter Plots:**  
  - Explored relationships between depth and magnitude, especially for earthquakes in North America.

### 2️⃣ Feature Engineering
- **Input Features (X):**  
  - 🗓 Date/Time (encoded for patterns like day, month, year).  
  - 📍 Latitude & Longitude.  
  - 🌐 Depth.  
  - 🗺 Region/Location.  
- **Target Variable (y):**  
  - 🌡 Magnitude (continuous variable).  

### 3️⃣ Model Development
- **Algorithm:** Linear Regression.  
- **Metrics:**  
  - 📉 **MSE (Mean Squared Error):** 0.052  
  - 📊 **R² Score:** 0.742  
    - Explains ~74.2% of the variance in earthquake magnitudes.



## 🔍 Results and Insights
- Magnitude predictions are reasonably accurate, with potential for improvement by adding features like geological activity indicators.  
- **Key Observations:**  
  - Most earthquakes are shallow, with depths between **0–10 km**.  
  - Magnitude values range from **3.5–5.25**.



## 📂 Files Included
- 📘 **EarthquakePrediction.ipynb:** Jupyter notebook for data preprocessing, modeling, and evaluation.  
- 📊 **Presentation:** Summarizes the project workflow and findings.



## 🚀 Future Work
- Include geological and environmental factors for better predictions.  
- Explore advanced models like non-linear regression or neural networks.  
- Incorporate real-time data updates for live earthquake monitoring.



## ✨ Author
**Hritik Singh**  
🎓 MS in Information Systems, Northeastern University  
📧 singh.hr@northeastern.edu  
[🔗 LinkedIn](https://www.linkedin.com/in/hritik-singh9919)
