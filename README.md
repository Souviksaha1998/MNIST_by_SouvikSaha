# MNIST_by_SouvikSaha

**Environment used for this project :** 
  google colab </br>
**Project Title :**
  HandWritten digit recognizer 
  I have done this project with famous mnist dataset. </br>
**Primary goals :** 
  1. Prepare and pre-process the dataset in manner that allows you
  to train a binary classifier (of your choice), that determines
  whether a digit is 7 or not 7.
  2. Draw the ROC curve of the predictions and explain your
  understanding of the same.
  3. Visualize the actual label and the predicted labels through subplots. </br>
**Build Status :** </br>
  I have downloaded the dataset from sklearn dataset. From this dataset i have only used "Data" and "Target" columns for my project.Then i created X for features and y 
  for labels and split the dataset into X_train , y_train , X_test , y_test.
  as the primary goal suggests , i have to create a detector that detect whether it is 7 or not 7.
  To plot the digit image i have used from matplotlib import pyplot. To get the image we have to reshape the data into 2D then plot it. 
  
 **Code Style  :**
  I have used Logistic Regression for this project. After fitting it into X_train , y_train , i got binary outputs.
  Now its time to predict, after predicting X_test values i compare it with Y_test_true and Y_pred_model and i got around 96% accuracy. I plot a ROC curve to check TRUE POSITIVE
  RATES and FALSE POSITIVE RATES. I found out , true positive rate is higher and false positive rate is lower , it means our model is good. 
  
  **Code Examples :** </br>
    I have created a "predict" function. we can use this function by this way "Predict(index)". It will show the actual image corresponding to the index number and the model 
    predicted number. </br>
  **Modules :** </br>
  I have used pandas , numpy , seaborn , matplotlib , sklearn modules. </br>
