# Real-Estate-Arbitrage

![image](https://user-images.githubusercontent.com/100448396/157686162-7517a3c6-9881-4669-9fa2-3a6c0f351fa7.png)


The main objective of Real Estate Arbitrage is buying a house in a low price, sell in a higher price and short period of time. Therefore it is reasonable to know the main variables that have a high influence on price.

Why?

Because theses main variables will alow you to notice whether the building is undervalued or not.

In this project, we will select the houses undervalued based on five or more key variables. For that, we need to make a good EDA(Exploratory Data Analysis) to see how the depedent variable (price) behave, how these variables have influence on price and whether the others variables are correlated with each other.

After the EDA, all transformations and adjusts that would be suitable on the data will be made. And, finally, we will make a Multiple Linear Regression with the selected variables as independent variable and the houses price as dependent variable. The Multiple Linear Regression will be evaluated through R2-score, statistical test and others metrics to see how good is our model to explain the depedent variable.

We will use a specific critria to consider a house as undervalued. The houses will be considered as undervalued if the difference between its predicted price (the price estimated for the model) and real price is higher than the RMSE (Root Mean Square Error). I have to say that this criteria is a little arbitrary, but I think it is valid.

We also need to know how much would be the profit if a real estate company, for example, wanted to buy some or all of the undervalued houses

## Results

If a real estate company had bought all of the undervalued houses, it could spend $666,721,234.

And if this company had sold all of the houses for the predicted price would earn a profit of $98,270,764.35

## Observation
It's important to clarify that this Multiple Linear Regression and this approach to determine the undervalued houses were made just for learning purposes. There are many ways to search for houses with price below the market price and, likely, it make a Multiple Linear Regression is just a simplistic way for that.



