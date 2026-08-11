# Sales Prediction Using Python

## OIBSIP Data Science Internship - Project 2

### Objective

The objective of this project is to predict product sales based on advertising expenditure across different media channels: TV, Radio, and Newspaper.

### Dataset

The project uses the Advertising dataset containing advertising expenditure and corresponding sales values.

### Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Workflow

1. Loaded and inspected the dataset
2. Checked data types and missing values
3. Removed an unnecessary index column
4. Performed exploratory data analysis
5. Created pairplots and scatter plots
6. Analyzed correlations using a heatmap
7. Split the data into training and testing sets
8. Trained a Linear Regression model
9. Trained a Random Forest Regression model
10. Evaluated both models using MAE, RMSE, and R²
11. Created a residual plot
12. Analyzed feature importance

### Model Results

Two regression models were compared:

- Linear Regression
- Random Forest Regression

Random Forest Regression performed better on the test data, achieving an R² score of approximately **0.9813**.

### Key Finding

TV advertising had the highest feature importance in the Random Forest model, followed by Radio advertising. Newspaper advertising had comparatively low feature importance.

### Files

- `Sales_Prediction.ipynb` - Jupyter Notebook containing the complete analysis and machine learning workflow
- `Advertising.csv` - Dataset used for the project