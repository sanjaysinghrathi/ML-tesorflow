# ML-TensorFlow

It consist a python jupyter notebook script to train & test traditional machine learning and deep learning models. It was developed to analyze huge genomic datasets. These datasets contain gene expression data for cancer patients where rows represent the patient and columns represent the genes. It is useful to find the difference between traditional ML models like logistic regression, support vector machine, random forest, multilayer perceptron model, gradient boosting machines, and K-nearest neighbor w.r.t deep learning tools like TensorFlow. It plot ROC curve and RSS score to visualize results for these tools.

Step 1: Read training and testing data from csv files having patients as rows and genes expression as columns. The last column contain the response for a patient.

Step 2: Train tradition ML model logistic regression, elastic net, support vector machine, multilayer perceptron model, random forest, gradient boosting machine and k-nearest neighbour. Save all models using joblib.

Step 3: Test each traditional model on test data to find the one with best accuracy.

Step 4: Train a deep learning model using TensorFlow (Keras) and test it on testing data.

Step 5: Plot ROC and RSS curves for best traditional ML model and TensorFlow.

Step 6: Compare Results. 
