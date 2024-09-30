Titanic - Machine Learning from Disaster is a Classification Competition on Kaggle to determine whether the passenger survived or not
***

After exploring the data I found that there is a columns has a high variation so I decided to cluster them using DBSCAN and T-SNE to determine how many clusters are there wit the elbow method and we've got clustersI used another technique to improve my score and F1 score by clustering the incorrect predictions and assigning them a separate label. I then built a secondary model to predict these newly labeled cases and added a new feature column to the original data. This approach ensures that the model becomes more sensitive to previously misclassified cases and enhances its predictive performance on challenging samples.

***
