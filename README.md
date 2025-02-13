# CarWorth: Intelligent Vehicle Pricing

This project predicts the prices of used cars based on a dataset containing various car attributes. The primary components of this project include a Jupyter Notebook (`car_price_predictor.ipynb`), a raw dataset (`quikr_car.csv`), and a cleaned dataset (`Cleaned car.csv`).

---

## File Overview

### 1. `car_price_predictor.ipynb`

This Jupyter Notebook contains the complete implementation of the project, including:

- Importing necessary libraries.
- Loading and exploring the raw dataset.
- Cleaning and preprocessing the data.
- Visualizing data trends.
- Building, training, and evaluating machine learning models for price prediction.

### 2. `quikr_car.csv`

This is the raw dataset used in the project. It contains 892 entries and 6 columns:

- `name`: Car model name.
- `company`: Manufacturer.
- `year`: Year of manufacture (stored as a string in the raw dataset).
- `Price`: Listed price of the car (stored as a string, sometimes inconsistent like "Ask For Price").
- `kms_driven`: Distance driven by the car (stored as a string, e.g., "45,000 kms").
- `fuel_type`: Type of fuel (Petrol/Diesel). Contains missing values.

### 3. `Cleaned car.csv`

This dataset is the result of data cleaning and preprocessing. It contains 816 entries and 7 columns:

- `Unnamed: 0`: Index from the original dataset.
- `name`: Car model name.
- `company`: Manufacturer.
- `year`: Year of manufacture (converted to integer).
- `Price`: Listed price of the car (converted to integer).
- `kms_driven`: Distance driven by the car (converted to integer).
- `fuel_type`: Type of fuel (Petrol/Diesel).

---

## Workflow

### Step 1: Import Libraries

The following Python libraries are used:

- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Matplotlib**: For visualizations.
- **Scikit-learn**: For machine learning model development.

### Step 2: Load and Explore Data

- Load the `quikr_car.csv` dataset.
- Inspect the dataset structure, data types, and missing values.

### Step 3: Data Cleaning

- Remove rows with missing or inconsistent data (e.g., "Ask For Price").
- Convert `Price` and `kms_driven` to integers.
- Standardize the `year` column to ensure valid integer values.

### Step 4: Exploratory Data Analysis (EDA)

- Visualize trends in car prices by manufacturer, year, and other features.
- Understand relationships between variables.

### Step 5: Model Training and Evaluation

- Split the cleaned dataset into training and testing sets.
- Train machine learning models (e.g., Linear Regression) for price prediction.
- Evaluate model performance using metrics such as Mean Absolute Error (MAE).

---

## How to Run the Project

### Prerequisites

1. Install Python (3.8 or later).
2. Install the required libraries using:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

### Steps

1. Place the files (`car_price_predictor.ipynb`, `quikr_car.csv`) in the same directory.
2. Open the Jupyter Notebook (`car_price_predictor.ipynb`).
3. Run the notebook cells sequentially to:
   - Load and clean the dataset.
   - Visualize data trends.
   - Train the prediction model.
4. Review model predictions and performance metrics.

---

## Outputs

- Cleaned dataset saved as `Cleaned car.csv`.
- Visualizations of trends and distributions.
- Predicted car prices for test data.

---

## Notes

- Replace `quikr_car.csv` with your custom dataset (if applicable) for custom predictions.
- Ensure consistent data formatting to avoid errors.

---

## Author

Brij Kishor

IIT PATNA

