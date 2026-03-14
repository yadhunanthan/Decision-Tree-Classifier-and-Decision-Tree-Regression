Step 1: Collect Data X = features (inputs) y = target (continuous value you want to predict) Example: diabetes_prediction_dataset

Step 2: Split Data Divided data into: Training set (to train the model) testing set (to check performance)

step 3: Create the Model Use a Decision Tree Regressor: from sklearn.ensemble import RandomForestClassifier ()

Step 4: Train the Model Teach the Model using training data: model.fit(X_train, y_train)

Step 5: Make Predictions Use the trained model to predict new values: y_pred = model.predict(X_test)

Step 6: cm=confusion_matrix(y_test,y_pred) cm Accuracy:0.93995
