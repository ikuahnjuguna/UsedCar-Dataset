# (Used Car Dataset Exploration)
## by (Joseph Njuguna)


## Dataset


This dataset contains records of used cars that  are up for sale. The dataset was downloaded from kaggle.com https://www.kaggle.com/datasets/shubham1kumar/usedcar-data/.
The following data wrangling activities were carried out on the dataset before exploration:
Quality issues:
a)Datatype conversion on respective columns to match the data in each column.
b)The mileage column had records with 0 mileage. These were removed from the analysis.
c)We noted cars with Kilometers driven above 1000000km.Upon reviewing the production year and selling price of the cars,this was most likely a data entry erro. The records were removed from the report.
d)Currency unit conversion from Indian Rupees to US Dollars.
Tidiness Issues:
a)Region,state or Province,City,torque and Sold Columns were removed from the dataset as they were not important for our analysis.


## Summary of Findings


Findings:
a)We noted that the selling price of the used cars is skewed to the right due to high selling price of some of the cars . However, the distribution is unimodal with most cars having a price tag of less than 10000 dollars.We further noted that the Selling price of a car is positively correlated to the car engine size and maximum power of the car. We noted a negative correlation between selling price,ownership and number of kilometers driven.
b)We noted that the Cars sold by individuals are much cheaper compared to cars sold by dealers.
c)For Cars with greater than or equal to 8 seats, the selling price decreases gradually because these cars have very low power, use manual transmission and are sold by individuals.These factors have negative correlation to the selling price of a car.
d)Automatic cars are more expensive than Diesel cars because automatic cars are more powerful than their Diesel counterparts.There is a positive correlation between selling price and max_power.
e)Manual cars have better mileage compared to automatic cars.Also to note ,diesel cars have better mileage compared to Petrol cars.CNG cars have the best mileage.
f)We noted a negative correlation between engine size and mileage, and a positive correlation between engine size and maximum power of the car


We will discuss these findings further in the explanatory presentation.


## Key Insights for Presentation

a)We will discuss how the Selling Price of a used car is correlated to each of the highlighted features in the exploratory phase.
b)We will further discuss the below interesting findings during the exploratory phase such
     1.Diesel cars are quite expensive compared to Petro, CNG and LPG cars.
     2.Cars sold by Dealers have a higher selling price compared to cars sold by individuals. 
     3. Automatic cars are more expensive compared to manual cars.
     4.There is a gradual increase in selling price for cars with Seats 4 to 7.We then see a gradual decline in the selling price for     cars with more than 7 seats.
     5.Test drive cars are the most expensive in terms of ownership, compared to cars in other ownership forms.


