Overview
This Jupyter Notebook (regression.ipynb) performs regression analysis on the California Housing Prices dataset. It includes data exploration, visualization, and regression models to predict median house values.

Dataset
The dataset contains 20,640 samples and 8 features:

- MedInc: Median income in block group
- HouseAge: Median house age in block group
- AveRooms: Average number of rooms per household
- AveBedrms: Average number of bedrooms per household
- Population: Block group population
- AveOccup: Average number of household members
- Latitude: Block group latitude
- Longitude: Block group longitude
- MedHouseVal: Median house value (target variable)

Notebook Structure
1. **Importing Libraries**: pandas, matplotlib, seaborn, scikit-learn.
2. **Loading Data**: Using fetch_california_housing from sklearn.datasets.
3. **Data Exploration**: Checking missing values, correlation heatmap.
4. **Data Preprocessing**: Standardization, splitting features and target.
5. **Model Implementation**:
   - Linear Regression (LinearRegression from sklearn.linear_model).
   - Ridge Regression with cross-validation (RidgeCV from sklearn.linear_model).
6. **Model Evaluation**: Cross-validation for performance assessment.

Key Steps
- **Exploration**: Checking data quality, correlation analysis.
- **Preprocessing**: Standardizing data for equal feature contribution.
- **Modeling**: Implementing Linear and Ridge Regression.
- **Validation**: Using cross-validation for robust evaluation.

Dependencies
Install required libraries using:
```
pip install pandas matplotlib seaborn scikit-learn numpy
```

Usage
1. Clone the repository.
2. Open `regression.ipynb` in Jupyter.
3. Run the cells sequentially to load, explore, preprocess, and model the data.
4. Evaluate models using cross-validation.

Results
The notebook provides insights into feature relationships and evaluates regression models for predicting housing prices in California.

License
Licensed under MIT License.

Acknowledgments
Dataset provided by `sklearn.datasets`. Inspired by various ML tutorials.
