# Predictive-Modelling-Graded-Project.
## Problem statement 1: Linear Regression

The comp-activ databases is a collection of a computer systems activity measures .
The data was collected from a Sun Sparcstation 20/712 with 128 Mbytes of memory running in a multi-user university department. Users would typically be doing a large variety of tasks ranging from accessing the internet, editing files or running very cpu-bound programs. 

As you are a budding data scientist you thought to find out a linear equation to build a model to predict 'usr'(Portion of time (%) that cpus run in user mode) and to find out how each attribute affects the system to be in 'usr' mode using a list of system attributes.

## Solution Approach:
* Performed Data cleaning, EDA, Data Encoding, Train-Test Split.
* Build Linear Regression Model using Sklearn and Statsmodel.

## Problem Statement 2:
Logistic Regression, LDA and CART

You are a statistician at the Republic of Indonesia Ministry of Health and you are provided with a data of 1473 females collected from a Contraceptive Prevalence Survey. The samples are married women who were either not pregnant or do not know if they were at the time of the survey.

The problem is to predict do/don't they use a contraceptive method of choice based on their demographic and socio-economic characteristics.

## Solution Approach:
* Performed Data Cleaning, EDA Process, Data Encoding, Train-Test Split.
* Buile Logistic Regression, LDA and CART Model.
* Optimized all the Models using Various Parameters.

## Inferences:

Comparison Between Models:

* Cart with stands the top model with Accuracy of 73% on train data and 67% on test data.
* Optimized Logistic Regression Model's Accuracy is 67% on Train data and 65% on Test data same is for LDA model as well.
* CART with GridsearchCV model's Accuracy is 81% on Train data and 63* on test data,The accuracy of test data is not comparable with train data this may be due to Overfitting.
* Comparison in Terms of Accuracy,Recall,Precision and AUC value:

* The CART model from all the other models seems to be performing the best in terms of Accuracy, Recall and Precision values.
* The CART model also gives the most important features according to which the split in the Decision Tree was made.
* 'Wife_age','No_of_children_born','wife_education' and 'Husband_education'(in same order of preference) are the most important variables in determining if a women uses 
   Contraceptive mathods.
