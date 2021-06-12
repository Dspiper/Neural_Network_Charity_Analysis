# Neural_Network_Charity_Analysis

## Overview: 
The purpose of this analysis is to help Alphabet Soup predict where to make investments through machine learning and neural networks. This is accomplished by creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup using the dataset containing more than 34,000 organizations that have received funding.  

## Results:
### Data Preprocessing
- What variable(s) are considered the target(s) for your model? The variable that is considered the target is the "IS_SUCCESSFUL" column values 
- What variable(s) are considered to be the features for your model? The variables that are considered the features would be the application_df without the "IS_SUCCESSFUL" column values  

![image](https://user-images.githubusercontent.com/77817870/121763050-ef8d3200-caed-11eb-9324-00930c317656.png)

- What variable(s) are neither targets nor features, and should be removed from the input data? The variables that were neither target nor features are the ID columns, “EIN” and “NAME”, which were dropped from the application_df. 

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? For the first model, two layers were used. The first layer had 80 neurons and the second layer had 30. In total, three activation functions were used, one in each hidden layer and one in the output layer. 
<img width="1008" alt="Screen Shot 2021-06-11 at 7 50 40 PM" src="https://user-images.githubusercontent.com/77817870/121763135-6e826a80-caee-11eb-85ed-c7522e371f47.png">

- Were you able to achieve the target model performance? I was not able to achieve the target performance of 75%. My initial test yielded an accuracy score of 0.725 (72%). Subsequent tests yielded accuracy scores of 0.727 (73%), 0.725 (72%), and 0.726 (73%).
- What steps did you take to try and increase model performance? For each attempt, I first increased the number of neurons in the two initial layers, then changed the activation functions of hidden layers or output layers, then added additional layers in the second and third attempts. 

## Summary: 
The overall results of the deep learning model had a loss rate of 0.556 (56%) and an accuracy rate of 0.725 (72%), which is interpreted that the model can predict the correct outcome 72% of the time. I would recommend using an SVM model to solve this classification problem. I think an SVM model would work because SVM can classify and create regression models with linear or nonlinear data and they are less prone to overfitting. 

