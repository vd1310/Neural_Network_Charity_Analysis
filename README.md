# Neural_Network_Charity_Analysis
## Overview of Project: Using machine learning and neural networks, analyse the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Below are the objectives:
#### Deliverable 1: Preprocessing Data for a Neural Network Model
#### Deliverable 2: Compile, Train, and Evaluate the Model
#### Deliverable 3: Optimize the Model

## Results: 

### Data Preprocessing
#### What variable(s) are considered the target(s) for your model?IS_SUCCESSFUL Column which is also used for splitting our preprocessed data into our features and target arrays
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/target.PNG)
#### What variable(s) are considered to be the features for your model?
##### APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, SPECIAL_CONSIDERATIONS, ASK_AMT
#### What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME. Also i later dropped 'SPECIAL_CONSIDERATIONS', 'INCOME_AMT'
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/drops.PNG)

### Compiling, Training, and Evaluating the Model. 
#### How many neurons, layers, and activation functions did you select for your neural network model, and why? 2 hidden layers, first layer has 80 neurons, the second has 30 there is also an output layer. Input layers have the "relu" activation function and "sigmond" for activation function / output layer
#### Were you able to achieve the target model performance? No, the model achieved 71% accuracy 
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/att3.PNG)
#### What steps did you take to try and increase model performance?
##### 1. Removed 'SPECIAL_CONSIDERATIONS', 'INCOME_AMT'
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/removed.PNG)
##### 2. Other category modified to <500 from 200
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/500.PNG)

## Summary: 
#### My deep learning neural network model achieved 71% accuracy thus failing to achieve the level of 75% and so we can say that the model is not that efficient. However by reducing the noise we could improve the accuracy from 53% to 71% and with further investigation the accuracy can be improved further
A. 
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/at1.PNG)
B. 
![alt text](https://github.com/vd1310/Neural_Network_Charity_Analysis/blob/main/att3.PNG)

