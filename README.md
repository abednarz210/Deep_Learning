# Deep Learning Homework: Charity Funding Predictor

![ImageCharity](https://andarba.org/asset/images/Charity-about-us.png)

# Overview 

Create an algorithm for the non-profit foundation, Alphabet Soup, to predict whether or not applicants for funding will be successful using machine learning and 
neural networks. 

# Resources 

* Jupyter
* Pandas
* Keras
* Tensorflow 
* Sklearn

# Results 

## Preprocess the Data

* Data read and preprocessed
* Target variable: 'IS_SUCCESSFUL'
* Feature variables: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE','ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT.' 
* Neither Target or Features and removed: 'EIN' and 'NAME'
 

## Compile, Train, and Evaluating the Model

* Alphabet Soup Charity Initial Model: 2 hidden layers 15 and 30 at 100 epochs with accuracy rate of 73% and loss at 54%
* Alphabet Soup Charity Optimization: 3 hidden layers 15, 30 and 45 at 100 epochs with accuracy rate of 73% and loss at 56% 
* Alphabet Soup Charity Optimization 2: 4 hidden layers 15, 30, 45 and 60 at 100 epochs with accuracy rate of 73% and loss at 57% 

# Summary 

I was unable to achieve the desired 75% accuracy rate for the outcome.  The additional layers did not increase the accuracy, but did increase the loss percentage. On the next attempt to achieve the 75% accuracy, I would try increasing the numeric amount used for two hidden layers and increase epochs.  



#### Resources/ Credits

*Image-(https://andarba.org/asset/images/Charity-about-us.png)
*Resources-(https://stackoverflow.com/questions/22320356/pandas-get-values-from-column-that-appear-more-than-x-times)
*Resources-(https://towardsdatascience.com/checkpointing-deep-learning-models-in-keras-a652570b8de6)


