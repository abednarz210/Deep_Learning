# Deep Learning Homework: Charity Funding Predictor

![ImageCharity](https://andarba.org/asset/images/Charity-about-us.png)

## Background

Create an algorithm for the non-profit foundation, Alphabet Soup, to predict whether or not applicants for funding will be successful using machine learning and 
neural networks. 

## Preprocess the Data

Data was read and preprocessed by dropping unnecessary columns, specifically 'EIN' and 'NAME.' The target variable was "IS_SUCCESSFUL." The feature variables
include: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE','ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT', 
'IS_SUCCESSFUL.'
 

### Compile, Train, and Evaluate the Model

Using TensorFlow, design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded 
organization will be successful based on the features in the dataset. Next, determine the number of neurons and layers in the created model to compile, train, 
and evaluate the binary classification model to calculate the model’s loss and accuracy. Save and export results to an HDF5 file. 


### Optimize the Model

Using your knowledge of TensorFlow, optimize your model in order to achieve a target predictive accuracy higher than 75%. If you can't achieve an accuracy higher than 75%, you'll need to make at least three attempts to do so.
Optimize your model in order to achieve a target predictive accuracy higher than 75% by using any or all of the following:

Adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:

Dropping more or fewer columns.
Creating more bins for rare occurrences in columns.
Increasing or decreasing the number of values for each bin.


Adding more neurons to a hidden layer.
Adding more hidden layers.
Using different activation functions for the hidden layers.
Adding or reducing the number of epochs to the training regimen.

NOTE: You will not lose points if your model does not achieve target performance, as long as you make three attempts at optimizing the model in your jupyter notebook.

Create a new Jupyter Notebook file and name it AlphabetSoupCharity_Optimzation.ipynb.
Import your dependencies, and read in the charity_data.csv to a Pandas DataFrame.
Preprocess the dataset like you did in Step 1, taking into account any modifications to optimize the model.
Design a neural network model, taking into account any modifications that will optimize the model to achieve higher than 75% accuracy.
Save and export your results to an HDF5 file, and name it AlphabetSoupCharity_Optimization.h5.


Step 4: Write a Report on the Neural Network Model
For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.
The report should contain the following:


Overview of the analysis: Explain the purpose of this analysis.


Results: Using bulleted lists and images to support your answers, address the following questions.



Data Preprocessing

What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?





Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.


Resources/ Credits

Image-(https://andarba.org/asset/images/Charity-about-us.png)
Resources-(https://stackoverflow.com/questions/22320356/pandas-get-values-from-column-that-appear-more-than-x-times)
Resources-(https://towardsdatascience.com/checkpointing-deep-learning-models-in-keras-a652570b8de6)


