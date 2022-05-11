# phishing_attack_detection_using_ai

Overview:

Phishing is a cybercrime in which a target or targets are contacted by email, telephone, or text
message by someone acting as a legitimate institution to trick individuals into providing sensitive
details such as personal information.

To overcome the above-written problem machine learning techniques (Artificial Neural Networks and XGBoost) has been used so that our computer can take real-time decisions and
can classify in advance that whether a particular site is a phishing site or not based on previously collected data.

Dataset:

File name - phishing_data.csv
We have taken a Kaggle dataset containing the details about phishing and legitimate website. he dataset consists of the URL of the website and several other features.

Architecture:

1. Collection of the data for testing purposes. We will collect the data from the dataset
and then use it for classification.
2. Then splitting the data into train and test sets. These sets will be divided in the ratio of
80:20. The train set will be used in training the model and the test set will be used in
verifying our model.
3. Building the model is applying the algorithms, i.e., implementing the ANN and the
XGBoost algorithms.
4. Training the model using the test set which will train the ANN and the XGBoost
models.
5. Importing links to the prediction step is the main step after the training of the model.
This is testing the model for accuracy and checking whether the model is
implemented successfully or not.
6. Deploying the model so that the model can be used for the checking of phishing
websites in the real world.
7. Fetching the results from the model and checking whether they are correct or not and
whether the accuracies are high or not.

