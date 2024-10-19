Breast Cancer Classification using Artificial Neural Networks (ANN)

This project focuses on classifying breast tumors as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) dataset. The dataset includes various features related to the cell nuclei taken from digitized images of breast tissue biopsies. The primary goal is to predict whether a tumor is malignant or benign based on these features.

Key Steps:
Data Cleaning and Preprocessing: Missing values were handled, and feature scaling was applied to standardize the data, ensuring all variables are on the same scale.

Model Building: An Artificial Neural Network (ANN) was built using Keras and TensorFlow. The network includes multiple layers with dropout layers to prevent overfitting. The activation function ReLU was used in the hidden layers, and Sigmoid was used in the output layer for binary classification.

Training the Model: The model was trained using the binary crossentropy loss function and the Adam optimizer. EarlyStopping was applied to stop the training process when the validation loss stopped improving.

Model Evaluation: The model was evaluated on the test set and achieved an accuracy of 97.36%. A confusion matrix was generated to further analyze the classification performance.

Results:
The ANN model performed exceptionally well, achieving a 97.36% accuracy in classifying breast cancer tumors. The confusion matrix displayed minimal misclassification, highlighting the model's effectiveness.

Tools and Libraries Used:
Python
Keras & TensorFlow for building the neural network
Scikit-learn for evaluation metrics and confusion matrix
Matplotlib for visualizing results
Conclusion:
This project demonstrates the potential of Artificial Neural Networks in medical diagnosis tasks, particularly in breast cancer classification. Through proper data preprocessing, model building, and evaluation, the model achieved high accuracy and can be considered a valuable tool for this classification task.
