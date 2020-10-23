# Airbnb housing project

This project focuses on exploring some of business questions relted to Boston and Seattle Airbnb data.  

## Project Set Up and Installation

This project is done on anaconda platform using jupyter notebook jupyter notebook. The detailed instruction of how to install anaconda can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).
To create a virtual environment see [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

in the virtual environment, clone the repository :
```
git clone https://github.com/abhishek-jana/AirBnb-housing-project.git
```
Packages used for this project are:
```
Numpy
Pandas
Matplotlib
Seaborn
```

Next, use the following command to install the necessary packages:

```
cd <pat to Airbnb-housing-project>
pip install -r requirements.txt
```
To install the dependencies.

### Dataset

The dataset for the project can be downloaded from [here](http://insideairbnb.com/get-the-data.html).


### Project structure

This projects aims to solve 4 business questions related to Boston and Seattle data.

Question 1: Which place is cheaper to stay? Boston or Seattle.

Question 2: What is the best time to visit these places?

Question 3: Which city is more popular with visitors?

Question 4: What are the popular areas to stay and what is the recommended type of housing?

### Description

In the repository please look into the jupyter notebook "What is your next destination? Boston or Seattle!.ipynb" for the analysis.

There are four types of datasets used for this project. "Boston_listing.csv", "Seattle_listings.csv", "Boston_calendar.csv" and "Seattle_calendar.csv".

The last two datasets has date, listing_id, price, avilable columns. If we compare the average housing price between Boston and Seattle using "price" column of the datasets we can determine which place is cheaper (answer to Question 1).

Using the "date" and "price" columns we can find out how the pricing changes throughout the year (answer to Question 2).

We can also find out the monthly availibility of the properties using the "available" column. Using this information we can answer Question 3.  

The first two datasets gives us information on how the pricing changes with  the property type, bedrooms, bathrooms, neighbourhood, zipcode etc. In this project I tried to find out the relation between neighbourhood and price and between property type and price. These two analysis can help determine Question 4 which aims to find out the popular places to stay in Boston/Seattle and finding recommended housing on these cities.

## Results

I found out that in terms of weather conditions, housing prices Seattle is a better place to travel compared to Boston. Please look into the notebook for detailed analysis

## Future work

In future work, I will show how to predict the Airbnb price using machine learning.


