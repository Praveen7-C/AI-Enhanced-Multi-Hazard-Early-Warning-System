# AI Enhanced Multi-Hazard Early Warning System

## Overview

The **AI Enhanced Multi-Hazard Early Warning System** is a Python-based project that leverages **Machine Learning, Geospatial Mapping, and Real-Time Weather Data** to predict, visualize, and analyze disaster risks such as **floods, droughts, and cyclones** in Indian cities.
It provides **multi-output hazard predictions**, **interactive visualizations**, and a **Streamlit-powered web app** to help governments, organizations, and communities prepare for and respond to natural hazards effectively.

---

## Features

* **Real-Time Data Collection:** Fetches weather data (temperature, rainfall, wind speed) from the **Open-Meteo API**.
* **Data Preprocessing & EDA:** Handles missing values, adds synthetic hazard labels, and performs **univariate, bivariate, and multivariate analyses** with Matplotlib & Seaborn.
* **AI-Powered Prediction:** Uses an **ensemble of Random Forest and Gradient Boosting** with a **VotingClassifier** wrapped in **MultiOutputClassifier** for multi-hazard classification.
* **Multi-Hazard Risk Assessment:** Predicts **Flood, Drought, Cyclone** probabilities for 30 Indian cities.
* **Interactive Visualizations:**

  * **Plotly** → hazard risk charts
  * **Folium** → disaster risk maps (green: low, orange: medium, red: high)
* **Model Persistence:** Saves and loads trained models with **Joblib**.
* **Deployment Ready:** User-friendly **Streamlit app** for hazard prediction based on user inputs.

---

## Technologies Used

* **Programming Language:** Python

* **Libraries & Tools:**

  * `requests` → Fetch weather data
  * `pandas`, `numpy` → Data preprocessing
  * `matplotlib`, `seaborn` → Exploratory Data Analysis (EDA)
  * `scikit-learn` → ML models (RandomForest, GradientBoosting, VotingClassifier, MultiOutputClassifier)
  * `plotly.express` → Interactive charts
  * `folium` → Interactive maps
  * `streamlit` → Web app deployment
  * `joblib` → Save/load models

* **Data Source:** Open-Meteo API (weather forecasts)

---

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Praveen7-C/AI-Enhanced-Multi-Hazard-Early-Warning-System.git
   cd AI_Enhanced_MultiHazard_EarlyWarning_System
   ```

2. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

   Example `requirements.txt`:

   ```
   requests
   pandas
   numpy
   scikit-learn
   matplotlib
   seaborn
   plotly
   folium
   streamlit
   joblib
   ```

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook AI_Enhanced_MultiHazard_EarlyWarning_System.ipynb
   ```

4. **Run Streamlit App(inside the jupyter notebook)**

   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Fetch weather data for Indian cities using **Open-Meteo API**.
2. Preprocess the dataset (handle missing values, encode features, add hazard labels).
3. Train ensemble ML models (**RandomForest + GradientBoosting with VotingClassifier**).
4. Evaluate using **classification reports, accuracy, and confusion matrices**.
5. Visualize results with **EDA plots, Plotly charts, and Folium maps**.
6. Save model using **Joblib** for deployment.
7. Use the **Streamlit app** to input weather parameters and get hazard predictions.

---

## Directory Structure

```
AI_Enhanced_MultiHazard_EarlyWarning_System/
├── AI_Enhanced_MultiHazard_EarlyWarning_System.ipynb   # Main Jupyter Notebook   
├── requirements.txt                                    # Python dependencies
├── README.md                                           # Project documentation
```

---

## Contributing

Contributions are welcome!
If you have ideas for improvements (e.g., integrating real hazard datasets, adding humidity/wind direction, deep learning models, or SMS/mobile alert systems), fork the repo and submit a pull request.

---

## License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## Acknowledgments

Special thanks to the following resources:

* **scikit-learn** → ML training & evaluation
* **Folium & Plotly** → Interactive visualizations
* **Pandas & NumPy** → Data preprocessing
* **Open-Meteo API** → Weather data source
* **Streamlit** → Model deployment

For queries, contact: **[praveen.chinna0765@gmail.com](mailto:praveen.chinna0765@gmail.com)**
