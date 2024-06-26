
# Data Science Pratical Application 2: 
# What drives the price of a car?

# Data:
The original dataset comes to us from Kaggle and it contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Our goal is to understand what factors make a car more or less expensive. 

# Data Cleanup
This dataset has 18 columns but there are 1215152 missing values in 14 columns. I also found there are outliners in data. We have to fix all these issues before starting data analytics.

# Data Analytics
We build and compare three regression models. By using GridSearchCV and turing hyper parameters, we can find the best model. After the fitted model is avaiable, we analyze permutation importances and model coefficients. The result tells us the list of key features that drives used car price up or down.

# Findings
- The most important feature is 'odometer' but it is negative relationship to price
- The top four important features are 'odometer', 'fuel', 'year' and 'manufacturer' 
- Diesel cars have high positive relationship to price more than gasoline cars
- Manufacturer ferrari, tesla and porsche have high positive relationship to price
- 12 and 10 cylinder cars has high positive relationship to price
- Clean and lien title status has high positive relationship to price
- Truck has high positive relationship to price
- New cars have high positive relationship to price

# Summary
By applying machine learning and data science techniques, we are able to analyze used car price dataset and identify key features. The findings confirms the common knowlege: Low mileage and new car drives the price up. On the other hand, high mileage and old car drives the price down. In addition, certain vehicle types sush as diesel cars and trucks can drive the price up. Certain manufacturer sush as Ferrari, Tesla and Porsche tends to be very high price.
