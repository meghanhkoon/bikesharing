# Bikesharing
NYC Citibike with Tableau

## Overview 
***Background***

Inspired by a recent trip to NYC, we are interested in starting up a similar bikesharing business for the state of Des Moines, Iowa.  Although Des Moines and New York City are vastly different, we decide to brainstorm ideas on how this potential business may work by first looking at how it works in NYC. To figure out how a bikesharing company might work in Iowa, we first need to pull data from a bike sharing company in NYC to understand the logistics. 

We specifically need to answer the following questions for a business proposal to a potential investor: 

- What type of customers use bikeshare programs? 
- Where are the most popular places for bikesharing? 
- How long are bikes being used? And by which customers? 

***Purpose***

The purpose of this analysis is to use Tableau to create visualizations to tell a story of how Bikesharing works in NYC using real-world bikesharing data. 

## Resources 
- Original Data Source: [Citi Bike Trip Histories From August 2019](https://ride.citibikenyc.com/system-data)
- Software: Tableau Public, Pandas, Jupyter Notebook 


## Results
### Links: 
- [NYC Citi Bike-Sharing Dashboard](https://public.tableau.com/app/profile/meghan.koon/viz/Module_15_16696632827210/NYCCitiBikeStory?publish=yes)
- [NYC Citi Bike-Sharing Analysis](https://public.tableau.com/app/profile/meghan.koon/viz/NYCCitiBikeSharingAnalysis_16698551962160/NYCCitiBikeSharingAnalysis?publish=yes)

### Data Analysis
Before creating additional visualizations for the Trip Analysis, we first had to change the Trip Duration to a Datetime format using Pandas and Jupyter notebook. To do so, we imported the data's csv, read it as a Pandas DataFrame, then converted the Tripduration column from int to a datetime format: 
```
# 3. Convert the 'tripduration' column to datetime datatype.
citibike_df["tripduration"] = pd.to_datetime(citibike_df["tripduration"], unit="s")
```

From the two Tableau Stories ([NYC Citi Bike-Sharing Dashboard](https://public.tableau.com/app/profile/meghan.koon/viz/Module_15_16696632827210/NYCCitiBikeStory?publish=yes) & [NYC Citi Bike-Sharing Analysis](https://public.tableau.com/app/profile/meghan.koon/viz/NYCCitiBikeSharingAnalysis_16698551962160/NYCCitiBikeSharingAnalysis?publish=yes)), we are able to analyze the data from NYC to see how it could possibly work in Des Moines, Iowa. Our findings are as follows: 

- 1. 

![1_Dashboard.png](bikesharing/Images/1_Dashboard.png)
- 
## Summary 


