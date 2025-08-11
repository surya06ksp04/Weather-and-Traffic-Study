# Urban Traffic & Weather Impact Study

This project analyzes how **weather conditions** (rain, temperature, air quality) impact **city traffic congestion** and predicts the best time to travel using a **Random Forest Regression model**.  
It features an **interactive dashboard** built with [Streamlit](https://streamlit.io/) for visualizing trends and predictions.

---

## Features
- **Data Integration**: Merges synthetic traffic and weather datasets.
- **Machine Learning**: Uses Random Forest Regressor to predict congestion levels.
- **Visualization**: Interactive Streamlit dashboard for data exploration and predictions.
- **Offline Friendly**: Works entirely with local CSV files—no API keys required.

---

## Dataset
Two sample datasets are included:
1. `traffic_data.csv` – Contains hourly congestion levels for a sample city.
2. `weather_data.csv` – Contains hourly temperature, rainfall, and air quality index.

Both datasets are synthetic and provided for demonstration purposes.

---

## Tech Stack
- **Language**: Python 3
- **Libraries**:
  - pandas
  - scikit-learn
  - matplotlib
  - streamlit
- **Model**: Random Forest Regressor

---

## Skills Demonstrated
Data preprocessing and merging multiple datasets

Feature engineering for machine learning

Model training, evaluation, and interpretation

Building and deploying an interactive data app
