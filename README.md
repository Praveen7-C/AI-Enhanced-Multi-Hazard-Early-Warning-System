# AI Enhanced Multi-Hazard Early Warning System

## Overview

The **AI Enhanced Multi-Hazard Early Warning System** is a Python-based project that leverages **Machine Learning and Geospatial Mapping** to predict, visualize, and analyze multiple disaster risks such as floods, earthquakes, wildfires, and storms.
It provides **real-time risk assessment** and **interactive disaster maps**, helping governments, organizations, and communities to prepare for and respond to natural hazards effectively.

---

## Features

* **Data Collection & Preprocessing:** Collects and processes disaster-related datasets from multiple sources.
* **AI-Powered Prediction:** Uses Random Forest, Gradient Boosting, and Voting Classifier models for multi-hazard predictions.
* **Multi-Hazard Risk Assessment:** Detects disaster categories (Flood, Earthquake, Wildfire, Storm).
* **Interactive Disaster Maps:** Dynamic hazard visualization using **Folium** and **Plotly**.
* **Performance Metrics:** Generates classification reports (Precision, Recall, F1-Score).
* **Visualization Dashboard:** Charts and graphs for hazard analysis.
* **Scalable Framework:** Can integrate with real-time APIs and satellite data.

---

## Technologies Used

* **Programming Language:** Python
* **Libraries & Tools:**

  * `pandas`, `numpy` → Data preprocessing
  * `scikit-learn` → Machine Learning models
  * `matplotlib`, `plotly.express` → Data visualization
  * `folium` → Interactive geospatial mapping
  * `requests` → API data fetching

---

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Praveen7-C/AI-Enhanced-Multi-Hazard-Early-Warning-System.git
   cd AI_Enhanced_MultiHazard_EarlyWarning_System
   ```

2. **Install Required Packages**
   Ensure Python 3.12, Jupyter Notebook, and Git are installed. Then install dependencies:

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
   plotly
   folium
   ```

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook AI_Enhanced_MultiHazard_EarlyWarning_System.ipynb
   ```

---

## Usage

1. Load disaster dataset(s) into the notebook.
2. Train ML models (Random Forest, Gradient Boosting, Voting Classifier).
3. Generate predictions for multiple hazards.
4. Visualize results using **interactive maps** and **charts**.
5. Export disaster risk maps and reports.

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
If you have ideas for improvements (e.g., integrating real-time APIs, deep learning, or automated alerts), fork the repo and submit a pull request.

---

## License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## Acknowledgments

Special thanks to the following technologies and resources that made this project possible:

* **scikit-learn** → for ML model training and evaluation.
* **Folium & Plotly** → for interactive mapping and visualization.
* **Pandas & NumPy** → for data preprocessing and analysis.
* **Open Data Sources** (NOAA, NASA, UNDRR) → for hazard datasets.

For any queries, contact: **[praveen.chinna0765@gmail.com](mailto:praveen.chinna0765@gmail.com)**

