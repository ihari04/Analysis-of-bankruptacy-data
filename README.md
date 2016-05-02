# Analysis-of-bankruptacy-data
Analysis of bankruptacy data using logisitic regression and regression trees

About the problem : To predict likelihood of bankruptcy using logistic and regression trees
About the data: the dataset has 13 variables including the independant variable. The predictor variables are different financial ratios and 
the dependant variable is binary response of 0 and 1.
Because this is classification problem, logistic regression and CART are used

Methodology:</br>
1. Logisitc model is fit on the data by AIC step wise selection</br>
2. p -cut off of 1/16 is determined using search grid technique over various cut offs </br>
3. Cross validation is done on the logistic model to understand it's out of sample performance</br>
4. Regression tree also fit on the data</br>
5. The performance of Logit and CART are measured on the basis of misclassification rate</br>


Major results:
1. AUC for logisitc is 0.89 , which is above the accepted cut off 0.7
2. k-fold classification for logistic gives a misclassfication rate of 33%
3. Misclassification rate of CART is 28%, 5% lesser than logistic 

