# Soil Moisture Prediction with Machine Learning


## This project demonstrates the use of machine learning to predict soil moisture based on temperature, humidity, and soil type.

## Dataset

The dataset used in this project contains the following columns:
- `temperature`: The temperature in degrees Celsius.
- `humidity`: The humidity percentage.
- `soil_type`: The type of soil (categorical variable).
- `soil_moisture`: The measured soil moisture percentage.

## Files

- `Soil_Moisture_Prediction.ipynb`: The Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `soil_moisture_data.csv`: The dataset used in this project.

## Usage

To run the notebook, you need to have Jupyter installed along with the required Python libraries. You can install the dependencies using:

```bash
pip install -r requirements.txt
=======
## Overview
This project predicts soil moisture levels using machine learning techniques. The dataset includes features such as temperature, humidity, and soil type, with the goal of predicting soil moisture based on these inputs.

## Dataset
The dataset `soil_moisture_data.csv` includes:
- `temperature`: Temperature in °C.
- `humidity`: Relative humidity in %.
- `soil_type`: Type of soil.
- `soil_moisture`: Measured soil moisture content.

## Installation
To run this project, install the required libraries:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/Hikitsuri/Soil_Moisture_Prediction_with_Machine_Learning.git
```
2. Navigate to the project directory:
```bash
cd Soil_Moisture_Prediction_with_Machine_Learning
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook Soil_Moisture_Prediction.ipynb
```

## Results
The model's performance is evaluated using Mean Absolute Error (MAE) and R-squared (R²) metrics. 

## License
This project is licensed under the MIT License.
>>>>>>> 49f997cc0ec9ea4905777471e24a025fadf85861