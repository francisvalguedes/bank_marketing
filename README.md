# Bank Marketing Prediction - Decision Tree

## Information
Msc. Francisval Guedes, Msc. Hareton Gomes

This work is part of the evaluation of theEEC1509 Machine Learning course of the Department of Computer Engineering and Automation Graduate Program in Electrical and Computer Engineering, Federal University of Rio Grande do Norte.

## The data
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

You can download the data from the [University of California, Irvine's website](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

Data attribute information:
   ##### Bank client data:   
   1. age (numeric)
   2. job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
   3. marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4. education (categorical: "unknown","secondary","primary","tertiary")
   5. default: has credit in default? (binary: "yes","no")
   6. balance: average yearly balance, in euros (numeric) 
   7. housing: has housing loan? (binary: "yes","no")
   8. loan: has personal loan? (binary: "yes","no")
   ##### Related with the last contact of the current campaign:
   9. contact: contact communication type (categorical: "unknown","telephone","cellular") 
  10. day: last contact day of the month (numeric)
  11. month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  12. duration: last contact duration, in seconds (numeric)
   ##### Other attributes:
  13. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  14. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  15. previous: number of contacts performed before this campaign and for this client (numeric)
  16. poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
  ##### Output variable (desired target):
  17. y - has the client subscribed a term deposit? (binary: "yes","no")


The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

## Machine Learning Model
The machine learning model implemented for prediction is the Decision Tree and is described in the link: [Model Cards](https://github.com/francisvalguedes/bank_marketing/tree/master/classification).


## Workflow

![image](https://user-images.githubusercontent.com/104702301/171174143-3cab4b4f-78c6-4ab4-bb3c-63a4b520ab2c.png)

A API está disponibilizada publicamente para teste no link: [API](https://bank-marketing-data-app.herokuapp.com/)

## Referencias:

[University of California, Irvine's website](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

[Bank Marketing Data - A Decision Tree Approach](https://www.kaggle.com/code/shirantha/bank-marketing-data-a-decision-tree-approach/notebook).

[Repository for EEC1509, a graduate course on PPgEEC about Machine Learning](https://github.com/ivanovitchm/ppgeecmachinelearning).
