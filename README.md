# Car_Price_Prediction

## OBJECTIVE

To build a regression model based on sample data and predict the price in the test data of the used cars.

![TpayT](https://user-images.githubusercontent.com/130181481/235348971-b2ff8d24-ec29-4c75-8be0-051705a48431.jpeg) 


## Granularity of Data

The Data in the provided dataset consists of cars In India. Each column provides data of company, car name, location, year, kilometer driven, fuel type, transmission, owner type, mileage, engine, power, seats, price.

## Shape of Data

#### The Training data excel file consists of data with 14 columns and 6020 rows. 

The 14 columns contain 14 variables namely: ID, Name, Location, Year, Kilometers_Driven, Fuel Type, Transmission, Owner type, Mileage, Engine, Power, Seats, New-Price and Price.

#### The Data contains 13 columns which help in classification of each car and there are a total of 1234 records which tells us there are 1234 cars details in the test data.

### The data is a mixture of both categorical and numerical data.

## Price Prediction

Regression Equation/ Best Fit Line Equation:  

### Y=M1X1+M2X2+C.

From the above Model, the Regression Equation can be created. The Equation is:

### Price = (-1805.51) + 0.5481*Company_name_num + 0.1964*Location_num + 0.8927*Year + (-0.00001)*Kilometers_Driven + 0.6576*Diesel + 0.0013*Engine_num + 0.0767*Power_num .
