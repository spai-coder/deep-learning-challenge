# deep-learning-challenge

### write a report on the performance of the deep learning model you created for Alphabet Soup.

## The report should contain the following:

### Overview of the analysis: Explain the purpose of this analysis.

### Results: Using bulleted lists and images to support your answers, address the following questions:

## Data Preprocessing

### What variable(s) are the target(s) for your model?
- "IS_SUCCESSFUL" column is the target variable from applilcation_df.

### What variable(s) are the features for your model?
- Every column from the dataframe are the features for my model.
### What variable(s) should be removed from the input data because they are neither targets nor features?
- "EIN" and "NAME" are removed from the input data because they were neither targets nor features.

## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I put 8 for the first hidden layer and 5 for the second layer. 
### Were you able to achieve the target model performance?
- No the result is 73%
### What steps did you take in your attempts to increase model performance?
- More layers were added include the hidden nodes. 
### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
- A model with more correlation between input and output would probably increase the prediction accuracy. More data cleaning and different activation functions can also achieve higher accuracy. 
