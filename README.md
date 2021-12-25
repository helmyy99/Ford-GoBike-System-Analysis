# Ford-GoBike-System-Analysis
## by Mostafa Helmy

The aim of this project is to provide a graphical summary of important features of a data set that includes information about individual rides made in a bike-sharing system by Ford covering the greater San Francisco Bay area.

## Dataset

> The Dataset consists of about 175 thousand entries and 16 features which are: Duaration, Start and End Stations' IDs and Names and Locations, Bike ID, User Type, Gender, and Birth Date. The dataset is consisted of mainly of categorical data and all nominal, except for the Duaration.


## Summary of Findings

> The dataset needed a few wrangling, there was some null values and false input data, but they were not much. The distribustions suggests the following: 
>> <p>The most spent duration is concentrated in the period under 1000 seconds</p>
>> <p>The most three common start stations are: Market St, San Francisco Caltrain Station 2, and Berry St</p>
>> <p>The most three common stations are: San Francisco Caltrain Station 2, Market St, and Montgomery St BART</p>
>> <p>The most common users are born between the years 1980s and 1990s</p>
>> <p>The ratio between customers and subscribers is 1:9</p>
>> <p>Males represent three quarters of the users</p>

> In the part of plotting members birth years counts, there was a single false entry which 1878, I assumed that the user intended to add 1978 but maybe typed it wrong, and then I fixed it. The stations number was too large (379), so I created new dfs for the start and end stations that contains only stations visited most to visualize them.

> <p>The Embarcadero had the highest IQR in terms of duration in both the Start and End stations</p>
> <p>Both Customers and Subscribers spend about the same duration time as each other</p>
> <p>Females tend to spend slightly more time</p>
> <p>Members born in the 2000s had the highest IQR in terms of duration</p>


> By comparing the gender and the user type features with the birth year feature we can see that:
>> <p>Males were always leading in the usage of bikes regardless of their birth year</p>
>> <p>The proportion of male subscribers is huge, which is logical because the proportion of male users in general is large</p>

> The Multivariate plots showed important correlations between features
>> <p>The fisrt and second graphs demonstrates the duration in each station spent by age categories</p>
>> <p>The last plot demonstrates the duration each age category spend in reference to their gender and user type</p>

> It was interesting that there were some stations that had members with an old age who spent a long duration in it.
