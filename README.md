# Zomato-Restaurant
Zomato API Analysis is one of the most useful analysis for foodies who want to taste the best cuisines of every part of the world which lies in their budget.Data has been collected from the Zomato API in the form of .json files(raw data). The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id.

## Install
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

## Run
In a terminal or command window, navigate to the top-level project directory and run one of the following commands:
```
jupyter notebook Zomato with best features with sklearn.ipynb
```
This will open the Jupyter Notebook software and project file in your browser.

## Dataset Information
The dataset contains 9551 data points collected with around 21 features.Zomato API Analysis is one of the most useful analysis for foodies who want to taste the best cuisines of every part of the world which lies in their budget.This analysis is also for those who want to find the value for money restaurants in various parts of the country for the cuisines. Additionally, this analysis caters the needs of people who are striving to get the best aggregate rating of the country and which locality of that country serves that cuisines with maximum number of restaurants.Data has been collected from the Zomato API in the form of .json files(raw data). The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id.

## Attribute information
- Restaurant Id: Unique id of every restaurant across various cities of the world.
- Restaurant Name: Name of the restaurant.
- Country Code: Country in which restaurant is located.
- City: City in which restaurant is located.
- Address: Address of the restaurant.
- Locality: Location in the city.
- Locality Verbose: Detailed description of the locality.
- Longitude: Longitude coordinate of the restaurant's location.
- Latitude: Latitude coordinate of the restaurant's location.
- Cuisines: Cuisines offered by the restaurant.
- Average Cost for two: Cost for two people in different currencies 👫 .
- Currency: Currency of the country.
- Has Table booking: yes/no.
- Has Online delivery: yes/ no.
- Is delivering: yes/ no.
- Switch to order menu: yes/no.
- Price range: range of price of food.
- Aggregate Rating: Average rating out of 5.
- Rating color: depending upon the average rating color.
- Rating text: text on the basis of rating of rating.
- Votes: Number of ratings casted by people.

## Output variable (desired target):
- Aggregate Rating

## Models trained On:
| Trained Model | Mean Squared Error | r2 score |
| --- | --- |
| Linear Regression with best features | 0.0310 |
| Linear Regression with best features using sklearn | 0.0318 | 0.9858 |

