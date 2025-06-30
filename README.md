**Air Sense Using AI** is a machine learning project that predicts the **Air Quality Index (AQI) category 3 in advance** using environmental and meteorological data. The model aims to provide **early warnings** and **health-based recommendations** to help individuals and authorities take timely precautions.

## Features

* Predicts **AQI Category** (e.g., Good, Moderate, Poor) using the **Random Forest Classifier**
* Uses a custom-built dataset with over 8,000 data points
* Supports **medium-term air quality forecasting**
* Focuses on improving public health through **data-driven insights**

## Technologies Used

* **Python**
* **Pandas**, **NumPy**, **Matplotlib**
* **Random Forest Classifier (Scikit-learn)**
* **CSV-based Dataset**

## Dataset

* Contains environmental variables like temperature, humidity, wind speed, and pollutant concentrations
* Preprocessed and engineered manually to ensure quality predictions

## How It Works

1. Load and preprocess data
2. Train the Random Forest Classifier on AQI-related features
3. Predict the AQI class for the next few days
4. Display the predicted category along with precautions

## Future Enhancements

* Real-time AQI prediction via API
* Interactive dashboard for visualization
* Cloud deployment for broader accessibility

## Project Structure

```
AirSenseAI/
├── data/                  # Dataset files
├── model/                 # Trained model files
├── src/                   # Python scripts for training and prediction
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
```

## Contributors

* Saumya 
