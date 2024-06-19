# At the first glance we can see that this is a classification problem

1. Loaded all dataset
2. Some exploratory data analysis
3. Prepared dataset for training (split the dataset into training and validation set)
4. Extracted input and output columns
5. Done some pre-processing of data(scaled the data,as the data was centred around median,but the outliers were affecting the prediction badly)
6. Trained different models
       i. Logistic regression
       ii. Random forest   classifier
       iii. XGBClassifier
8. Ensembled the above 3 model for better results and entropy
9. Uploaded the probabilities in submission file
