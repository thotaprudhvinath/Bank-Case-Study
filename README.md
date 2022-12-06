# Bank-Case-Study
__Problem Statement -__ Given various fratures about a customer like Age, Incomme,Loan_Amount,Loan_Intent, Home_Ownership etc...,predict if in case the loan is given, will the customer default or not on the loan payments.

__Task -__ Prepare the data and build a model to predict if a customer is going to default or not on the Loan payments.

These are the steps that are followed will doing the project
<b>step- 1 :-<b/> loading the data
<b>step- 2 :-<b/> Document the below mentioned points properly.
- Identify the input and output/target variables.
- Here,x dataframe has input variables.
- and y dataframe has output/target variable.
- As we know the target variable is given then the type of the problem comes under __supervised learning.__
- Target variable has __nominal data__ so, __classification algorithm__ and __evaluation metrics__ can be applied on the data
<b>Step - 3:</b> Split the dataset into Training and Testing
- Here, the data is splited into 75:25 ratio
<b>Step - 4:</b>Data preparation on train data:
- serperating catogorical and numerical data in x_train dataframe
- applying __Stadardization__ on Numerical data.
- applying __OneHot Encoding and Lable Encoding__ on Catagorical data.
<b>Step - 5</b>: Data preparation on test data:
<b>Step - 6</b>: Model Training Phase - Use all the algorithms mentioned below to train separate models:
- KNN
- Logistic Regression
- Support Vector Machines
- Decision Trees
- Random Forest
<b>Step - 7</b>: Evaluating the preformance of the model by using accuracy_score metrics
