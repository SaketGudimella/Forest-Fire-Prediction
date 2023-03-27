# Forest-Fire-Prediction


The code first loads the forest fire dataset from a CSV file using Pandas and preprocesses the data by one-hot encoding the categorical features and scaling the continuous features using StandardScaler from Scikit-learn. The data is then split into training and testing sets using train_test_split from Scikit-learn, with 80% of the data used for training and 20% for testing. A logistic regression model is trained on the training data, and the accuracy of the model is evaluated on the testing data. The code predicts whether a forest fire occurred or not, using a binary classification approach.
