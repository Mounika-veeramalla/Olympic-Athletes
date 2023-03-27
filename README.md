# Olympic Athletes
### (Athens 1896 - Rio 2016:A sprint through the years)

## Project Objective
    Worked with a historical dataset on the modern Olympic Games, which includes all the games from Athens 1896 to Rio 2016. The data was scraped from www.sports-reference.com in May 2018.

    The dataset athlete_events.csv contains 271’116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event. Our goal is to create a machine learning model that predicts the winner of Olympic games.

### Methods Used
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas, jupyter, numpy
* plotly, seaborn, matplotlib
* geopandas
* sklearn, pycaret


## Project Description
### Our work flow: 
    Approach: Supervised ML
    Classes: Gold/Silver/Bronze/NoMedal
    Clean data and make decisions
        -Use National Olympic Committees (NOC),not countries
        -Remove Year, but not City
    Find the best models with PyCaret
    Fix imbalance, check feature importance
    Manual tuning on the selected models
    Visualize data
    Develop story incl. fun-facts

### Data Insights: Olympic Outliers
    Youngest participant ever -  Dimitrios Loundras (Greece), Athens 1896 - 10 years Bronze in Gymnastics Men's Parallel Bars, Teams
![alternative text](reports/img/youngest_winner.png)
    
    Age of the oldest participant ever - John Quincy Adams Ward (USA) - 97 years
    
![alternative text](reports/img/oldest_winner.png)

    USA & Soviet Union in the Lead
    
![alternative text](reports/img/Medals by NOC(countries).png)
 
    Number of participants according to the age
    
![alternative text](reports/img/Participants_age.png)

    US goldmedals per category
     
![alternative text](reports/img/US_goldmedals.png)

    Participation of Women through out the Summer Olympics

![alternative text](reports/img/Women participating in Summer Olympics.png)

    Participation of Women through out the Winter Oympics
    
![alternative text](reports/img/Women participating in winter Olympics.png) 


#### Other Members:

 - [Alexej Khalilzada](https://github.com/alexej-khalilzada)
