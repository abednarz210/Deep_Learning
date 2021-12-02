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

* Alphabet Soup Charity Initial Model:2 hidden layers 15 and 30 at 100 epochs with accuracy of 73% and loss at 54% 
![Screen Shot 2021-12-01 at 11 25 08 PM](https://user-images.githubusercontent.com/86257908/144362842-ddaeda2b-68a4-4f57-8e59-a43bb9b98e48.png)
![Screen Shot 2021-12-01 at 11 25 58 PM](https://user-images.githubusercontent.com/86257908/144362927-a1a56a42-71d6-4e6a-b72b-67270b5164a3.png)


* Alphabet Soup Cahrity Optimization Model: 2 hidden layers 15, 30 and 45 at 100 epochs with accuracy of 73% and loss at 56% 
![Screen Shot 2021-12-01 at 11 27 57 PM](https://user-images.githubusercontent.com/86257908/144363117-132f6af0-b1db-446b-8c43-d370607e42a8.png)

# Summary 






#### Resources/ Credits

*Image-(https://andarba.org/asset/images/Charity-about-us.png)
*Resources-(https://stackoverflow.com/questions/22320356/pandas-get-values-from-column-that-appear-more-than-x-times)
*Resources-(https://towardsdatascience.com/checkpointing-deep-learning-models-in-keras-a652570b8de6)


