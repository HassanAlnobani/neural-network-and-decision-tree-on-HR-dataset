# neural-network-and-decision-tree-on-HR-dataset
Data Loading and Exploration:
The dataset is loaded using Pandas from a CSV file named "HR-Employee-Attrition.csv."
The basic information about the dataset, such as column names, data types, and non-null counts, is displayed.
Descriptive statistics of numerical columns are shown.

Data Preprocessing:
Duplicate rows are checked and handled.
Missing values are checked (using isna().sum()) and found to be zero.
Some categorical columns are converted to numerical representations using label encoding.
Unnecessary columns are dropped.

Data Visualization:
Visualization using histograms and a pie chart for gender distribution.

Feature Importance:
Feature importance is evaluated using the Extra Trees Classifier.

Model Building:
A neural network model is constructed using TensorFlow and Keras.
The model consists of multiple layers, including input, hidden, and output layers.
The model is compiled with binary crossentropy loss and the Adam optimizer.

Model Training and Evaluation:
The model is trained on the training data (X_train and y_train) and evaluated on the test data (X_test and y_test).
Accuracy, precision, recall, and F1-score are calculated.
The confusion matrix is visualized using a heatmap.

Comparison with Decision Tree:
A Decision Tree classifier is also trained and evaluated for comparison with the neural network model.

Performance Metrics and Visualization:
Classification reports, including precision, recall, and F1-score, are displayed for both models.
Confusion matrices are visualized.

Conclusion:
The code provides a comprehensive overview of the data preprocessing, model building, and evaluation steps for predicting employee attrition.
