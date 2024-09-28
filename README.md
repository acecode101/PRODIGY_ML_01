House Price Prediction using Linear Regression

This project implements a linear regression model to predict house prices based on key features such as square footage (LotArea), number of bedrooms (BedroomAbvGr), and number of bathrooms (FullBath). The model is trained and validated on a dataset using Python and Scikit-learn.

Workflow:

Data Loading: Train and test datasets are loaded from CSV files.

Feature Selection: Selected features include LotArea, BedroomAbvGr, and FullBath.

Data Preprocessing: Data is split into training and validation sets. Features are scaled using StandardScaler to normalize the input data.

Model Training: A linear regression model is trained on the scaled training data.

Evaluation: The model's performance is evaluated using Mean Squared Error (MSE), and actual vs predicted prices are visualized.

Prediction: Predictions are generated on the test data and saved to a CSV file.

Visualization: Several plots are generated:

Scatter plot for actual vs predicted prices.

Distribution of residuals (errors).

Bar chart comparing actual and predicted prices for the first 20 samples.

Key Libraries:

Pandas

Scikit-learn

Matplotlib

Seaborn

Results:

Mean Squared Error (MSE): Calculated for the validation set.

Predictions for the test set are saved as test_with_predictions.csv.

Visualizations:

Actual vs Predicted House Prices

Distribution of Residuals

Comparison of Actual vs Predicted Prices (First 20 Samples)
