# Bitcoin-Price-Prediction-using-ml

### Bitcoin Price Prediction using Machine Learning

This project aims to predict Bitcoin prices using machine learning techniques. The workflow involves data preprocessing, model training, and evaluation of the model's performance.

#### Key Steps and Processes:

1. **Data Loading and Preprocessing**:
   - The dataset consists of historical Bitcoin prices.
   - The data is loaded into a Pandas DataFrame, and initial exploratory data analysis (EDA) is performed to understand its structure and key statistics.

2. **Feature Engineering**:
   - The main feature used is the historical price data.
   - A new column, 'Prediction', is created by shifting the 'Price' column by a specified number of days (e.g., 30 days) to set up the target variable for future price prediction.

3. **Model Selection**:
   - A Support Vector Regressor (SVR) with a Radial Basis Function (RBF) kernel is chosen for the prediction model.
   - The dataset is split into training and testing sets to evaluate the model's performance.

4. **Model Training and Prediction**:
   - The SVR model is trained on the training dataset.
   - Predictions are made for the test dataset as well as for future prices (e.g., next 30 days).

5. **Evaluation**:
   - The predicted prices are compared against actual prices to assess the model's accuracy.
   - The model's predictions and actual prices are visualized for better understanding and analysis.

6. **Results**:
   - The model's predictions are displayed alongside the actual prices to highlight the performance and potential accuracy of the SVR model.

#### Key Outputs:
- A table showing the first few rows of the dataset with the 'Price' and 'Prediction' columns.
- Model predictions for the test set and the next 30 days.
- Visual representation of the predicted vs. actual prices.

