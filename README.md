Instructions:

You have been asked to build a predictive model that can classify the cab driver's tip i.e. based on the trip data, will they receive a tip or not. If they receive a tip, will it be low, standard or good. You are required to build a decision tree, using the scikit-learn library to make the predictions.

The trip data has been preprocessed and is stored in 'trip_data.csv.zip'.

Create a Jupyter notebook (or Python script) and load the data in 'trip_data.csv.zip' and perform the following steps:

Extract the following features that will be used to build the model: 'VendorID', 'RatecodeID', 'PULocationID', 'DOLocationID', 'passenger_count', 'trip_distance', 'fare_amount', 'extra', 'mta_tax', 'tolls_amount', 'improvement_surcharge', 'total_amount', 'trip_type', 'congestion_surcharge', 'tip'

Note: The column 'tip' contains the labels (i.e. the predicted output). The labels are: no-tip, low, standard or good.
Split the dataset into a training set and a test set; The test set should comprise 30% of the dataset. Ensure the data is randomized and that stratified samples are obtained. Scikit-learn has a module that is useful to split the data according to this criteria.

Create a decision tree to classify the cab driver's tip. Ensure that you perform these steps:

3.1 Instantiate the Decision Tree Classifier object and set the parameter for criterion to either 'gini' or 'entropy'. Also set the max_depth to 5.

3.2 Build the Decision Tree model using the training set.

3.3 Use the model to make predictions with the test set.

3.4 Evaluate the accuracy of the predictions, using the accuracy score, and display the accuracy that was achieved.

NOTE: If the prediction accuracy is less than 80%, increase or decrease the value of max_depth in 3.1 above. Run the code for steps 3.1 to 3.4 to retrain the classifier and evaluate the predictions. Did the accuracy improve? If not, choose a value for max_depth to improve the accuracy.

Visualize the decision tree using the graphviz library (or your preferred library/tool).

Inspect the visualization and summarize the results using 2-5 sentences. What are your thoughts on the way the decision tree split the data to make the predictions and the accuracy that was obtained?
