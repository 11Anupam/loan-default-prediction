# loan-default-prediction
The main idea is to predict weither a person will default or not , based on historical data.
The number of people by loan status are as follows:
![no of people by loan status ](https://user-images.githubusercontent.com/113086952/204488090-6434e0ce-f7fa-468d-8c4d-f38a4bf09ab1.png)

Home Ownership Type:

![home ownership type](https://user-images.githubusercontent.com/113086952/204488594-77f92a26-5561-4fd2-922e-4dcd5d76c797.png)


Correlation Matrix:

![download](https://user-images.githubusercontent.com/113086952/204488252-33850be2-c760-4052-a29f-7ca35240eb13.png)

Scatter plot:

![download1](https://user-images.githubusercontent.com/113086952/204488452-a606d619-5c24-43da-98de-6a8ccbf3fb73.png)

Loan Holders according to type and status :

![loan holders via type and status](https://user-images.githubusercontent.com/113086952/204488786-83c8e51a-80b9-4103-9606-0bcce013e510.png)



The Model Accuracies are as follows:
1)Dicision Tree:
DT_model: recall: 0.62
DT_model: precision: 0.89
DT_model: F1 Score: 0.73
DT_model: accuracy: 0.90

2)Random Forest:
RF_model: recall: 0.66
RF_model: precision: 0.96
RF_model: F1 Score: 0.78
RF_model: accuracy: 0.92

3)XGBoost:
xg_model: recall: 0.69
xg_model: precision: 0.97
xg_model: F1 Score: 0.81
xg_model: accuracy: 0.93
