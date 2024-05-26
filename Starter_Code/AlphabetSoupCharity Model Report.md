# Report on the Neural Network Models for Alphabet Soup Charity
## Overview of the analysis
The purpose of this analysis is to implement and develop a neural network model for Alphabet Soup Charity. Alpjhabet Soup has requested a predictive model  to detemine which organizations are likely to success after recieving funds. in order to achieve this, we used a dataset that contains various features that is related to charity organizations and their funding success.

## Results

### Data Preprocessing
- Targeted variables: "IS_SUCCESSFUL" that represents whether an organization that recieved funds were succeeful (1) or not (0).

- Features: "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "STATUS," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," and "ASK_AMT."

- Removed variables: "EIN" and "NAME".

### Compiling, Training, and Evaluating the Model

1. The model consists of 2 hidden layers. The first hidden layer have 12 neurons and "relu" activation function. The second hidden layer have 6 neurons and "relu" activation function. 
The neurons chosen were just random guesses which was iterated to see which one fit the best.
2. The model was not able to achieve the target model performance.
3. Addisional hidden layer was added, more neurons were added in attempt to achieve higher model accuracy.

## Summary 
In summary, the analysis involved creating and evaluating deep learning neural network model to predict the success of charitable organizations receiving funding from Alphabet Soup. The model achieved the highest accuracy of 72.66%.
Using a model with higher correlation between input and output would likely help to result a higher prediction accuracy. This could be done by doing extar data cleaning and using a model with a different activation function and iterating numbers of neurons until higher accuracy is met.
