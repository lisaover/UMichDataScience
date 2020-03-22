# UMichDataScience
Introduction to Data Science in Python by the University of Michigan

## Week 2 Assignment
* __Part 1:__  
The code in Part 1 loads the olympics dataset (olympics.csv), which was derrived from the Wikipedia entry on All Time Olympic Games Medals, and does some basic data cleaning. The columns are organized as # of Summer games, Summer medals, # of Winter games, Winter medals, total # number of games, total # of medals. This dataset is used to answer questions about All Time Olympic Games Medals.

* __Part 2:__  
The code in Part 2 uses the census data from the United States Census Bureau to answer a set of questions. Counties are political and geographic subdivisions of states in the United States. This dataset contains population data for counties and states in the US from 2010 to 2015. 

## Week 3 Assignment
The code in assignment 3 loads, manipulates, and merges three datasets: 
* Energy data from the file _Energy_Indicators.xls_ is a list of indicators of energy supply and renewable electricity production from the United Nations for the year 2013  
* GDP data from the file _world_bank.csv_ is a csv containing countries' GDP from 1960 to 2015 from World Bank  
* Sciamgo Journal and Country Rank data for Energy Engineering and Power Technology from the file _scimagojr-3.xlsx_ ranks countries based on their journal contributions in the aforementioned area. 

The project involved extracting information from the merged dataset to answer questions about the data.

## Week 4 Assignment
The code in assignment 4 loads, manipulates, and merges three datasets:  
* Housing data for the United States for all homes at a city level, _City_Zhvi_AllHomes.csv_, has median home sale prices at a fine grained level  
* College towns is a list of university towns in the United States which has been copy and pasted into the file _university_towns.txt_  
* GDP over time, in quarterly intervals, of the United States in current dollars from Bureau of Economic Analysis, US Department of Commerce, in the file _gdplev.xls_. 

__Hyppothesis:__ University towns have their mean housing prices less effected by recessions. 

This project involved runing a t-test to compare the ratio of the mean price of houses in university towns the quarter before the recession starts compared to the recession bottom.
