# Creating-Spam-Filter-Using-Own-Naive-Bayes-Classifier
For this Classification problem we used a database consisting of 5500+ text messages labeled "Spam" (malicious) or "Ham" (benevolent).
Since our data were not belonging to a distribution and our output variable was categorical and not numerical we could not use the Naive Bayes classifier from Scikit-Learn. Instead we created our own Naive Bayes classifier. 
Methodology : 
Imported data, performed EDA , shuffler and split data into training - validation - test.
Created a Classifier ("NaiveBayersForSpam") Class with methods train, predict, score.
Trained the Classifier with the training data.
Acquired confusion matrix to calculate performance of the classifier. (accuracy : 97.7%).
Created a new classifier and calculated the new confusion matrix. (accuracy : 97.9%).
