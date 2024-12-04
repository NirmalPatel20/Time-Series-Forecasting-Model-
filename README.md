# Time Series Forecasting Model

## Overview
This repository contains a project focused on forecasting sunspot activity using time series analysis techniques. The project leverages **Facebook Prophet** for modeling daily, monthly, and yearly sunspot trends, providing insights into the cyclical nature of sunspot activity. By combining preprocessing, model training, and evaluation, the project demonstrates practical applications of forecasting for real-world datasets.

---

## Features
- **Forecasting**: Predict daily, monthly, and yearly sunspot counts with high accuracy.
- **Data Preprocessing**: Transform raw datasets for compatibility with time series forecasting models.
- **Performance Metrics**: Evaluate predictions using MAE, MAPE, and R² scores.
- **Visualization**: Display actual vs. predicted values with interactive and static plots.

---

## Technologies Used
- **Python Libraries**: 
  - `pandas` for data manipulation.
  - `matplotlib` for plotting results.
  - `Prophet` for time series modeling.
  - `sklearn` for evaluation metrics.
- **Tools**: Facebook Prophet for advanced forecasting.

---

## Installation
Follow these steps to set up and run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sunspot-forecasting.git
   cd sunspot-forecasting
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   > The `requirements.txt` file includes `pandas`, `Prophet`, and other necessary dependencies.

---

## Usage
1. Add your dataset to the `data/` folder. Use the provided dataset as a template.
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Project-3.ipynb
   ```
3. Follow the notebook steps to:
   - Preprocess the dataset.
   - Train the forecasting model using Facebook Prophet.
   - Evaluate the model's performance.
   - Visualize predictions.

---

## Project Structure
```
├── Project-3.ipynb      # Main Jupyter Notebook
├── data/                # Folder for datasets
├── outputs/             # Folder for forecast results and plots
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## Results
- Forecasts for daily, monthly, and yearly sunspot data.
- Visual comparisons of actual vs. predicted values, showcasing trends and patterns.
- Performance metrics including:
  - Mean Absolute Error (MAE)
  - Mean Absolute Percentage Error (MAPE)
  - R² Score

---

## Dataset
The project uses publicly available sunspot data.
