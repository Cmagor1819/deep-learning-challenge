# For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

1. What variable(s) are the target(s) for your model?

* The target variable is the 'IS_SUCCESSFUL' column from the application_df DataFrame.

2. What variable(s) are the features for your model?

* The variable(s) that are the features are every other column from the application_df DataFrame. This was obtained by dropping the 'IS_SUCCESSFUL' column from the original DF.

3. What variable(s) should be removed from the input data because they are neither targets nor features?

* The variable(s) that should be removed are the 'EIN' and 'NAME' columns, because they were not either targets nor features for the dataset.

# Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model and why?

* For the first attempt, I used 8 hidden_nodes1 and 5 hidden_nodes2, becuase they were just a random guess as to which to iterate in the second attempt.

2. Were you able to achieve the target model performance?

* No I was not able to achieve the target model performance of 75%.

3. What steps did you take in your attempts to increase model performance?

* The steps I took to increase model performance were, adding more layers, removing columns, adding more hidden nodes, and switching activation functions.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Ultimately, the model performance was roughly 73% accurate in its predictions of the classification problem. To achieve a higher prediction accuracy, using a model with greater correlation between the input and output would most likely help. By doing further data cleanup, along with utilzing different activation functions in the model and iterating until the higher performance accuracy is achieved, are steps to accomplish that.
