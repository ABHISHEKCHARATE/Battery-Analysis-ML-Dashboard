# Battery-Analysis-ML-Dashboard
A machine learning-based dashboard for predicting battery capacity using features like ambient temperature and resistance. It includes interactive visualizations, KNN and Random Forest models for predictions, and performance metrics such as MSE and R² to evaluate model accuracy.


## Features
- **Interactive Dashboard**: Visualize battery performance across multiple metrics.
- **Machine Learning Models**: KNN and Random Forest for predicting battery capacity.
- **Performance Metrics**: Evaluates models with MSE and R² for accuracy.
- **Battery Aging Insights**: Visualize how impedance, electrolyte resistance (Re), and charge transfer resistance (Rct) change as the battery ages.

## Dataset
The dataset contains operational data from Li-ion batteries under various conditions (charge, discharge, impedance). It includes parameters like:
- **Ambient Temperature**
- **Battery Impedance**
- **Re (Electrolyte Resistance)**
- **Rct (Charge Transfer Resistance)**

## Machine Learning Models
- **KNN (K-Nearest Neighbors)**: A simple, non-parametric model that predicts battery capacity based on the closest data points in feature space.
- **Random Forest**: An ensemble learning method that combines multiple decision trees to improve prediction accuracy and avoid overfitting.

## How It Works
1. **Data Preprocessing**: Scales the input features for better model performance.
2. **Model Training**: Uses KNN and Random Forest to predict battery capacity.
3. **Visualization**: Visualizes battery parameters and prediction results.

## Requirements
- Python 3.6+
- Dash
- Plotly
- scikit-learn
- pandas

## Run the App
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
