# EV-Traffic-Predictor
Import necessary libraries: Imports pandas, scikit-learn (for the model), and matplotlib (for plotting).
Sample data: Creates a sample dataset with TimeOfDay and EVTrafficCount. Replace this with your actual EV traffic data.
Data preparation: Separates the features (time of day) and target (EV traffic count) into X and y.
Train-test split: Divides the data into training and testing sets using train_test_split.
Model training: Creates a Linear Regression model and trains it on the training data.
Prediction: Uses the trained model to predict EV traffic on the test set.
Evaluation (optional): You can add code to evaluate the model's performance using metrics like R-squared, Mean Squared Error, etc.
Plotting: Visualizes the actual vs. predicted values using matplotlib.
Prediction for a new time: Shows how to use the model to predict EV traffic for a specific time of day.
