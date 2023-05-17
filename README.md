# Heart-Disease-prediction

Early detection of heart diseases is critical in the treatment and management of cardiovascular diseases, wherein machine learning can be a powerful tool in detecting a potential heart disease diagnosis. But they are not detected in the early stages due to the impractical costs of the tests available. Thus, a fast, real-time and reliable system that predicts the chances of a patient having heart disease in an optimized manner is required. 

# Dataset 
Dataset used for this project is Heart Disease UCI. -- https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

The dataset consists of 76 attributes; out of which only, 14 attributes are used for our project to predict heart disease.

This system is implemented using the following modules. 

1.) Collection of Dataset 

2.) Data Pre-Processing 

3.) Balancing of Data 

4.) Model Building

5.) Disease Prediction using Trained Model.

Perform Exploratory data analysis (EDA) on features of dataset to analyse relationship among different features. We use correlation matrix which implies correlation values among all features including target also. Heatmap of correlation matrix. Analyse sex feature with target, Age feature with target, and sex, age both with target using box plot and violin plot. Max heart rate with target whether having disease or not using scatter plot.

Like, Supervised learning is the type of machine learning in which machines are trained using well "labelled" training data, and on the basis of that data, machines predict the output. 

# ALGORITHMS used are: -  

SUPPORT VECTOR MACHINE (SVM): 

Support Vector Machine is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems.The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

Effective in high dimensional spaces. ● Still effective in cases where the number of dimensions is greater than the number of samples. ● Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient. 

RANDOM FOREST ALGORITHM:

Random Forest is a supervised learning algorithm. It is an extension of machine learning classifiers which include the bagging to improve the performance of Decision Tree. It combines tree predictors, and trees are dependent on a random vector which is independently sampled.

It works in four steps: 

● Select random samples from a given dataset. 

● Construct a Decision Tree for each sample and get a prediction result from each Decision Tree. 

● Perform a vote for each predicted result. 

● Select the prediction result with the most votes as the final prediction


LOGISTIC REGRESSION ALGORITHM:

Logistic regression predicts the output of a categorical dependent variable. Therefore, the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.

K-NEAREST NEIGHBOUR(KNN) ALGORITHM:

K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.
K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.

EVALUATION METRICS:

ACCURACY SCORE is used to measure the performance of trained model on testing dataset that already partitioned using train_test_split.

# CONCLUSION
After performing the machine learning approach for training and testing we find that accuracy of the KNN algorithm is # 89% 
which is highest among all algorithms




