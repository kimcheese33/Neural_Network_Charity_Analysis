# Neural Network Charity Analysis

## Overview

The purpose of this project was to use ML Neural Networks to analyze charity data to determine if a cause will be successful or not. To accomplish this, I preprocessed the data; compiled, trained, and evaluated the neural network model; and finally optimized the model. I am attempting to reach a target model performance of 75%.   

## Results
   
### Data Preprocessing
  
- Target variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
- Feature variable: IS_SUCCESSFUL
- Removed variables: EIN, NAME
   
### Compiling, Training, and Evaluation the Model

- For my first attempt, I used 2 hidden layers with 80 neurons in the first and 30 neurons in the second. I used a ReLU activation function on the hidden layers and a Sigmoid function on the output layer 
- For my second attempt, I used 3 hidden layers with the same neurons in the first two and 20 neurons in the third. I used ReLU activation function for the third hidden layer
- For my third attempt, I went back to hidden layers, but changed the neurons. I had 90 in the first and 30 in the second. The activation functions were the same
- For my fourth attempt, I changed everything back to be the same as the first attempt. I changed the epochs to go from 100 to 150
- for my last attempt, I changed everything back to the first attempt, except I changed the output layer's activation function to be Tanh instead of Sigmoid

I was not able to get to the target model performance of 75%. However, I was able to get close on my last attempt, which was 73%. It appears that changing the activation function from Sigmoid to Tanh on the output layer improved my model the most.

## Summary

Overall, the model improved the most when I changed the activation function. The model got worse when I added hidden layers, neurons, and epochs. Next time I would recommend using a logistic regression model or SVM instead.
  

    
