# Algerian Forest Fires Prediction

This project is a Machine Learning web application that predicts the risk of forest fires in Algeria based on environmental parameters. It uses a **Ridge Regression** model trained on real-world data to provide accurate and reliable predictions for the Fire Weather Index (FWI).

## Features

- Predicts Forest Fire Weather Index (FWI) using user-input environmental factors.
- Interactive web interface built with **Flask** and **Tailwind CSS**.
- Model trained on the Algerian forest fire dataset.
- Easy-to-use form for entering temperature, humidity, wind speed, rainfall, and other relevant features.

## How to Run

1. **Install dependencies**  
   Ensure you have Python installed, then run the following command to install required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Start the application**  
   Run the Flask application with:
   ```bash
   python application.py
   ```

3. **Open your browser**  
   Visit [http://localhost:5000](http://localhost:5000) to access the prediction interface.

## Input Features

- **Temperature (°C)**
- **Relative Humidity (%)**
- **Wind Speed (km/h)**
- **Rainfall (mm)**
- **FFMC (Fine Fuel Moisture Code)**
- **DMC (Duff Moisture Code)**
- **ISI (Initial Spread Index)**
- **Classes** (0 or 1)
- **Region** (0 or 1)

## Model

- **Type:** Ridge Regression
- **Files:**
  - `models/ridge.pkl` (trained model)
  - `models/scaler.pkl` (feature scaler)

## Author

- **Nhat Nguyen**

## License

This project is for educational purposes.
