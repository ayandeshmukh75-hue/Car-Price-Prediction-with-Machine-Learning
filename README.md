# Car Price Prediction with Machine Learning

1. About the Project

Buying or selling a used car can be difficult when it comes to deciding the right price. The price of a car depends on several factors, such as its age, current price, kilometres driven, fuel type, transmission, and ownership history.

In this project, I have built a Machine Learning model using Python to estimate the selling price of a car based on these details. The project helped me understand how regression algorithms can be used to solve real-world prediction problems.

2. Project Objectives

- Predict car selling prices using Machine Learning.
- Explore and clean the car dataset.
- Understand the relationship between car features and selling prices.
- Perform feature engineering by calculating car age.
- Visualize car price distributions and trends.
- Train and evaluate a regression model.
- Test the model with new car details.

3. Dataset

The project uses the dataset `car data.csv`.

The dataset contains information about cars, including:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

The target variable is `Selling_Price`, which the model learns to predict.

4. Technologies and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

5. Project Workflow

### 1. Data Loading
Loaded the CSV dataset using Pandas and explored the available columns.

### 2. Data Cleaning
Checked missing values and duplicate records, and prepared the dataset for analysis.

### 3. Feature Engineering
Created a new feature called `Car_Age` using the manufacturing year.

### 4. Exploratory Data Analysis
Created visualizations to understand selling price distribution, compare fuel types, and explore the relationship between car age and price.

### 5. Data Preprocessing
Used One-Hot Encoding for categorical features and imputation pipelines to prepare the data for model training.

### 6. Model Training
Split the dataset into training and testing sets and trained a Random Forest Regression model.

### 7. Model Evaluation
Evaluated predictions using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² score.

### 8. Price Prediction
Used the trained model to estimate the selling price of a new car based on its features.

6. Visualizations

The project generates the following graphs:

- Selling Price Distribution
- Average Selling Price by Fuel Type
- Car Age vs Selling Price
- Actual vs Predicted Car Prices

7. Model Evaluation

The model is evaluated using three metrics:

- **MAE:** Measures the average absolute difference between actual and predicted prices.
- **RMSE:** Measures prediction error while giving more weight to larger errors.
- **R² Score:** Indicates how well the model explains price variation on the test dataset.

The actual metric values are generated when the notebook is executed.

8. How to Run the Project

1. Clone or download this repository.
2. Open `Car_Price_Prediction.ipynb` in Google Colab.
3. Upload the `car data.csv` dataset when prompted.
4. Run all code cells in order.
5. Review the graphs, evaluation metrics, and sample price prediction.

9. What I Learned

While working on this project, I practised data cleaning, exploratory data analysis, feature engineering, categorical data encoding, regression modelling, and model evaluation using Python.

I also learned how to build a complete Machine Learning workflow, from loading a dataset to making predictions on new data.

10. Conclusion

This project demonstrates how a regression model can be used to estimate used-car selling prices based on the available car details. It provided practical experience with Python libraries and the main steps involved in developing a Machine Learning project.

The predicted price is an estimate based on the dataset and should not be treated as a guaranteed market price.

11. Future Improvements

- Try other regression algorithms and compare their performance.
- Perform hyperparameter tuning.
- Add more car features and a larger dataset.
- Build a simple web application for interactive price prediction.
