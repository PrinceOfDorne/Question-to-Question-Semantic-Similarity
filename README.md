# Question-to-Question-Semantic-Similarity

The dataset used is available here: https://www.kaggle.com/c/quora-question-pairs/data

Due to lack of processing power, had to stop training at 2nd epoch on training accuracy of around 80% while it was still improving. The model still generates test accuracy of 78%. The dataset was divided into train, test and validation set in the ratio of 6:3:1. Total number of datapoints were 600,000+. Since validation accuracy was more than training accuracy after the first epoch, I think K-Fold cross-validation may give even better results.
