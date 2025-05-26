# What's the use case:
Here machine learning is applied in 'Bank Marketing' dataset to predict whether a person will purchase term deposit or not which is the target column 'y' here. The project's main task is to predict that target value (yes/no) if given unknown data. Based on the training data how well can it perform and how accurate is it. Well all the models performed pretty well and among them Logistic Regression had an accuracy of 90.734% (best). 


# What's the process:

  1. EDA: First, the dataset was analyzed to understand the shortcomings and imperfections through plotting graphs, detecting outliers, correlation heatmap, density plot 
      etc. This part was beneficial because it helped to understand the shape and the overall scope of the dataset. Which features depend on each other

    
  2. Data Preprocessing: Missing data problems were solved in the data preprocessing part. Encoding (to turn the categorical values to numerical values) and scaling the data      were also done in this part.

  
  3. Data splitting and Data Training: The entire dataset was split into 70/30 -> of which 70% was training data and the rest 30% was testing data. In total 4 models were 
     run while training the dataset:

         (a)  Logistic Regression 🎯
         (b)  Decision Tree
         (c)  K-Nearest Neighbor Algorithm (KNN)
         (d)  Neural Network

  4. ROC curve based on AUC score, Confusion Matrix, Classification Report and Accuracy:

     When the dataset is imbalanced just the accuracy score is not enough. To better understand which model performed the best we need to see the classification report along      with the confusion matrix (in how many false and true instances it predicted the target accurately) and also roc curve. All these things help us to understand the            situation better.  


      ![accuracy](https://github.com/user-attachments/assets/e0e1c9ea-bfa1-4f14-9916-70ae43b93f1a)


# Improvements:

A few more things are planned to be done in the near future. Like to make the imbalance dataset into a balanced one by using data oversampling techniques like SMOTE, Synthetic data could've been really helpful. A little more emphasis on EDA by removing more outliers, and in terms of neural network, the right amount of neurons in all the layers could've really boosted the accuracy score even more. While the current state is promising and pretty decent as well, there's always room for improvement, and further iterations will aim to make the model even more accurate.

`A report for this project has also been attached. You can go through that to have a better understanding.`


`Soon, the model will be deployed. Stay tuned for that`
