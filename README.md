# Objective 
The project analysis the spread of airbnb units in City of Seattle. The main objective of the project is to identify high priced airbnb in City of Seattle and suggest places which would be of interest to an affluent traveller. It aims to answer the following business question. 

# Business Question
1. Which neighbourhood would an affluent traveller (ie a traveller willing to spend more on accomodation) to Seattle most likely find his place of stay via airbnb?
2. What is the types of accomadation available to his choice if he is willing to spend more?
3. Do owners in Airbnb (especially low priced accomodation) try to compensate their low priced rentals by imposing minimum stay restrictions. Eg: Do low priced accomadation require tenants to higher number of minimum nights stay compared to high priced accomodation. 

# Methodology Adopted
The project adopted CRISP-DM methodology to analze the data and arrive at the results. THe steps include Business understanding
, Data understanding, Data preparation, Modeling, Evaluation, Deployment.

# Libraries Used
Folium: It is used for creating for plotting data on maps, in this case plotting airbnb locations based on latitude and lingitude in map of seattle

Jenkspy: The algorithm is used to create frequency distribution. It divides the given set of number into n number of groups where n is defined by the user. It does so by identifying the points where the data can be split, resulting in groups with least variance of within group elements. It does this by using an iterative process till least variance is obtained within each group.

OS: OS library is used to get the current path.

Pandas: Used to create dataframe for better analyzing of data.

# Results
As per the plot, we find that the downtown in city of Seattle has more concentration of high priced (high & very high included) Airbnbs compared to the rest of the area. Further analysis of high priced area reveal that th mean price of high priced airbnb is $1027.99. The decriptive statistics of the data tells us that high priced airbnb has a standard deviation of 446, which shows in fairly large spread in data. This is reflected in minimum price of $690 and maximum price of $5400 within high and very high price bracket. 

In terms of the type of airbnb which one finds in the high and very high price bracket, it is usually as entire home / apartment type amounting for 259 (73%) units out of total 352 total listing in high and very high price bracket. In case of negihbourhood, Central Business district, Pike-Market, International district and Belltown accounts for most of high and very high priced airbnb

Finally, when we look at the correlation results for the entire dataset between, prices and minimum nights that one is required to stay, we find it at -0.023, which shows existence of almost no relation between both the variables. 

# Files in the repository
The repository contains a readme and project file. Readme files gives a overview and technical details of the project while the project file is a jupyter notebook file with codes in it. 









