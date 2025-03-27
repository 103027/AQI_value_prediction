# Data Science Project: Weather and Air Quality Index (AQI) Analysis

## 📌 Project Overview
This project focuses on weather data analysis, rain prediction, and Air Quality Index (AQI) analysis. It involves data scraping, feature engineering, exploratory data analysis (EDA), and machine learning models to predict AQI values and analyze environmental factors affecting air quality.

## 🔍 Features
- **Weather Data Analysis**: Evaluates patterns in weather conditions.
- **AQI Analysis**: Assesses air pollution levels in different regions.
- **AQI Prediction Model**: Predicts AQI values using machine learning algorithms.
- **Data Scraping**: Extracts real-time AQI data from IQAir using Selenium and Beautiful Soup.
- **Exploratory Data Analysis (EDA)**: Identifies key trends and insights in the dataset.

## 📂 Dataset Information
The AQI dataset includes the following features:
- **Country Name**
- **AQI Score**
- **Condition** (Air Quality Level: Good, Moderate, Unhealthy, etc.)

The AQI prediction dataset includes:
- **City**
- **Date & Time**
- **Weather Conditions** (Wind, Temperature, etc.)
- **Pollutants** (PM2.5, PM10, NO2, CO, CO2, O3)
- **AQI Score**

## ⚙️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Selenium, Beautiful Soup)
- **Jupyter Notebook** for development and visualization
- **Machine Learning Models**:
  - Random Forest
  - Linear Regression
  - Gradient Boost
  - Deep Neural Networks (DNN)

## 🚀 Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repository
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## 📊 Results & Insights
- The model provides accurate AQI predictions based on environmental factors.
- High pollutant levels (PM2.5, PM10) significantly impact AQI values.
- Weather conditions such as wind and temperature influence air quality trends.

## 🔮 Future Enhancements
- Integrate real-time AQI data API for continuous monitoring.
- Improve model accuracy using additional meteorological features.
- Deploy the model as a web application for public access.
