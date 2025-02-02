Observations: The 3 models I used were Lasso, Ridge, and LinearRegression. I am unsure exactly why this is the case, but both Ridge and LinearRegression 
were overfitted even when polynomial degree was set to 1, numerical features were scaled, and categorical features were encoded. I played around with the 
Alpha for both Ridge, but did not end up getting results that indicated no overfitting. The best score given by GridSearchCV for all 3 models were low (x < 0.3). 
The coefficient for Ridge and LinearRegression seem to indicate that there is a positive correlation with how new the car is and how expensive it is, while Linear
Regression seems to indicate that there is a negative correlation with how much mileage a car has and how expensive it is.  
