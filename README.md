# Bank-Case-Study
__Problem Statement -__ Given various fratures about a customer like Age, Incomme,Loan_Amount,Loan_Intent, Home_Ownership etc...,predict if in case the loan is given, will the customer default or not on the loan payments.

__Task -__ Prepare the data and build a model to predict if a customer is going to default or not on the Loan payments.

These are the steps that are followed will doing the project

<br><b>step- 1 :-<b/> loading the data<br/>
  
__step- 2 :-__ Document the below mentioned points properly.
1. Identify the input and output/target variables.
2. Here,x dataframe has input variables.
3. and y dataframe has output/target variable.
4. As we know the target variable is given then the type of the problem comes under __supervised learning.__
5. Target variable has __nominal data__ so, __classification algorithm__ and __evaluation metrics__ can be applied on the data

<br>__Step - 3:-__ Split the dataset into Training and Testing<br/>
a. Here, the data is splited into 75:25 ratio
  
<br><b>Step - 4:-</b>Data preparation on train data:<br/>
a. serperating catogorical and numerical data in x_train dataframe
b. applying __Stadardization__ on Numerical data.
c. applying __OneHot Encoding and Lable Encoding__ on Catagorical data.
  
<br>__Step - 5__:- Data preparation on test data:<br/>
  
__Step - 6:-__ Model Training Phase - Use all the algorithms mentioned below to train separate models:
1. KNN
2. Logistic Regression
3. Support Vector Machines
4. Decision Trees
5. Random Forest
  
__Step - 7:-__ Evaluating the preformance of the model by using accuracy_score metrics
