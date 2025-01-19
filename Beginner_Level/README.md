# Boston House Price Prediction

This project involves designing and implementing a regression model to predict Boston house prices based on a dataset containing features such as the number of rooms, crime rates, and other relevant factors. The solution includes data preprocessing, model selection, training, and evaluation.

## Dataset

The dataset contains various features related to Boston housing, such as:
- **CRIM**: Per capita crime rate by town.
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq. ft.
- **INDUS**: Proportion of non-retail business acres per town.
- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- **NOX**: Nitric oxide concentration (parts per 10 million).
- **RM**: Average number of rooms per dwelling.
- **AGE**: Proportion of owner-occupied units built prior to 1940.
- **DIS**: Weighted distances to five Boston employment centers.
- **RAD**: Index of accessibility to radial highways.
- **TAX**: Full-value property-tax rate per $10,000.
- **PTRATIO**: Pupil-teacher ratio by town.
- **B**: \(1000(Bk - 0.63)^2\) where \(Bk\) is the proportion of Black individuals by town.
- **LSTAT**: Percentage of lower status of the population.
- **MEDV**: Median value of owner-occupied homes in $1000s (target variable).

## Project Workflow

### 1. Data Preprocessing
- Load the dataset and inspect its structure.
- Handle missing values if any.
- Perform feature scaling (e.g., standardization or normalization).
- Explore and visualize the dataset for insights (e.g., correlation heatmaps, histograms).

### 2. Model Selection
- Use regression models such as:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Use cross-validation to select the best-performing model.

### 3. Model Training
- Split the dataset into training and testing sets.
- Train the selected model(s) on the training set.
- Optimize hyperparameters using techniques like Grid Search or Random Search.

### 4. Model Evaluation
- Evaluate the model on the test set using metrics such as:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - \(R^2\) score
- Compare the performance of different models.

### 5. Results and Insights
- Present the best model's performance.
- Provide insights into feature importance and their influence on house prices.

## Requirements

To run this project, ensure you have the following dependencies installed:

```bash
numpy
pandas
scikit-learn
matplotlib
seaborn
```

Install them using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd boston-house-price-prediction
```

3. Run the Python script:

```bash
python main.py
```

4. View the model evaluation metrics and predictions.

## Files

- `HousingData.csv`: Dataset file.
- `main.py`: Main script for data preprocessing, model training, and evaluation.
- `README.md`: Project documentation.

## License

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
