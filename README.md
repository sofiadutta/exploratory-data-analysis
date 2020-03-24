# Exploratory Data Analysis

### Project 1 - Data Characterization
The data I obtained shows the gross and annual salaries for employees of the Baltimore City Government, from July 2017 to June 2018.

* I found this data through the suggestions for project 1 ideas on Blackboard.

* I thought given the income inequality discussions around tax season and new tax laws being implemented this year, I would study if there is any income inequality in Baltimore City Government.

* The source website is Baltimore City Open Government site
* The file I downloaded from the url above is named "Baltimore_City_Employee_Salaries_FY2018.csv".
* There is no cost to accessing this data.
* Accessing this data does not require creation of an account.
* Accessing this data does not violate any laws.
* This data does not appear to have been previously analyzed based on a Google search.
* A preliminary survey of the data indicates there are 13,683 rows, 7 columns, and the file size is 1.5 MB.

### Project 2 - Data Characterization
#### About the data:
The obtained data shows film permits granted for New York City. Permits are generally required when asserting the exclusive use of city property, like a sidewalk, a street, or a park. I found this data through the suggestions for project 2 ideas on Blackboard.

#### My story:
Growing up I have watched a lot of American movies and TV shows. Many of these have shown New York City. After I came to the USA I myself visited many of the places in New York City (NYC) and visualized the movies and shows I had watched as a kid. I did not get to see an actual film shoot though. So, when I saw this data, the data scientist in me thought I should figure out when do movies actually shoot in NYC. Following questions came to my mind:

* Can this data tell me popular timing of day for film shoots?
* The answer to the first question is that most popular time of day for shooting is between 5 AM and mid-day.
* Theater "shoots" are an outlier when events per hour of day are analyzed and we see a lot of them seem to happen in hour "zero" or mid-night. However, this is not an issue from the perspective of analysis as this could be reasonable and not an anomaly. This is because a lot of theater shows start in the evening and can run upto mid-night.
* Can this data tell me the popular day of the week when shooting activities occur?
* Weekday-wise permit counts and the normalized value of the permit count show that weekends are outliers when shoots per day are considered.
* We were able to conclude from the number of shoots per day that weekdays are fairly well balanced in matters of shooting activities.
* Can it tell me popular months of year for film shoots?
* So, the answer to our third question is TV shoots happen in phases. Mostly in Fall months but some in Spring months as well. Movie shoots happen starting around Spring, peaking around summer and again a bit in the Fall.
* Winter in New York city is very beautiful due to all the snow but are the shooting really happening in the harsh winter conditions of NYC?
* The graph for normalized value of total number of permits per month answers our fourth question that winter is really a bad time to shoot in New York City as the number of events go down but there still are a non-zero number of shooting activities happening. This is especially true for TV shows.
* I know some Bollywood movies have shot in Staten Island because of a large Indian community in that area but is it a popular location in general?
* The graph of normalized value of total number of permits per borough and type of activity shows that Staten Island is NOT in-fact a popular shooting location.
* I like a lot of web series and watch Youtube stars like Casey Neistat who films in New York City. Given the popularity of Youtube in recent times are web shoots are rising in the city?
* After filtering out some top "shooting" categories we were able to see a clear rising trend of WEB shoot activity in New York City!
* Which locations in New York City are popular for movie shoots?
* WEST 48th STREET, New York City, New York is near Times Square. Intuitively this seems to be a reasonable location to be considered popular.
* Data properties and access information:
* Data available through NYC Open Data site.
* Downloaded file named: "Film_Permits.csv".
* There is no cost to accessing this data.
* Accessing this data does not require creation of an account.
* Accessing this data does not violate any laws.
* This data does not appear to have been previously analyzed based on a Google search.
* A preliminary survey of the data indicates there are 40,682 rows, 14 columns, and the file size is 15.4 MB.

### Final project, Data 601, Spring 2019 - Analysis of New York State Fire Department Fallen Heroes Data
* Dataset 1: New York State Fallen Firefighters Memorial Roll of Honor data
* Dataset 2: Fire Department Directory for New York State

#### Merging column: Fire Department Name
#### About the data:

* My final project combines two different datasets. The datasets cover different aspects of New York State Fire Departments.
* The first dataset; "New York State Fallen Firefighters Memorial Roll of Honor", contains the names, ranks department names, dates of death and locations on Memorial Wall of Firefighters who have sacrificed their lives in order to save others.
* The second dataset; "Fire Department Directory for New York State", contains an annually update list of names, location, phone numbers and Division of Homeland Security and Emergency Services (DHSES) ID for Fire Departments in New York State. The data is collected and maintained by the Office of Fire Prevention & Control (OFPC) within DHSES.

* I found this data through the suggestions for project data ideas on Blackboard.

#### My story:

* Firefighters are one of the most amazing and selfless people in the world. I beleive that most humans, given a choice, would always save themselves. Firefighters on the other hand are the brave few people in the world who would jump into a fire to save another person.
* There have been many tragedies in this world. However, only a handful of them have had an impact as big as the attack on September 11th, 2001.
* When I saw these two datasets, I thought I could combine the data to identify patterns about such incidents from temporal data of fatalities in fire departments of New York State. I think this data analysis will help me see the impact of that one incident in comparison to others.
* While exploring patterns in the combined dataset, following questions came to my mind:
* Everyone knows about September 11th, 2001 and that people died but can it be determined from the combined data, which county most of the firefighters came from?
* Key Observation - Combining the two datasets I am able to infer that on September 11, 2001, New York County happened to face a severe crisis, in which hundreds of firefighters gave their lives.
* The firefighters that sacrificed their lives on 9/11 came from New York County.
* Story time - 9/11 was one of the biggest terrorist attacks in American History on American soil killing thousands of people.
* From online searches I found, on that day: "Of the 2,977 victims killed in the September 11 attacks, 412 were emergency workers in New York City who responded to the World Trade Center."
* "This included: 343 firefighters (including a chaplain and two paramedics) of the New York City Fire Department (FDNY)".
* My dataframe - top_date_of_death_county_df shows that on 9/11, 2001 New York County had in-fact had 343 fatalities.
* During 9/11 was there a fire department where most of the fatalities occurred?
* During 9/11 the fire department located at "9 metrotech center", Brooklyn, New York seems to be the station from which most of the firefighters operated.
* Intuitively this looks reasonable as the World Trade Center is in lower Manhattan that is very close to Brooklyn by waterways.
* It is understandable that there will be few high ranking officials directly involved in rescue operations. Does the combined data tell us the ranks of the firefighters that sacrificed their lives?
* I was able to determine that most fatalities on 9/11 happened for the "Firefighter" rank.
* The second highest fatalities were for "Lieutenant" rank followed by "Captain" and "Battallion Chief".
* Is there any incident comparable to 9/11 in terms of fire fighter fatalities? Where did such an incident occur?
* Using my analysis I was also able to determine that there is no incident, as per the datasets, that can compare to 9/11, in terms of fatalities. However, it looks like on August 2nd, 1978 there was an incident that might have caused some fatalities. After googling around, I found that the Waldbaum Fire of August 2, 1978 had killed six firefighters.
* Which fire departments across the state of New York have had the most fatalities? Can the top ten fatal locations be represented visually with information about the most fatal incident for that location?
* I was also able to visualize using a map of New York State, the dates of the most fatal incident, alongwith count of fatalities. I was able to visualize the most fatal incident ranked by top ten most fatal locations across the state of New York.

#### Data properties and access information:
Data available through Fire Department Directory Data from NYS Open Data site and New York State Fallen Firefighters Memorial Roll of Honor.

#### Downloaded file named: "New_York_State_Fallen_Firefighters_Memorial_Roll_of_Honor.csv" and "Fire_Department_Directory_for_New_York_State.csv".

#### These two data sources can be merged based on the Fire Department's name column that can be found in both files.

* There is no cost to accessing this data.
* Accessing this data does not require creation of an account.
* Accessing this data does not violate any laws.
* This data do not appear to have been previously analyzed based on a Google search.
* A preliminary survey of the data in New_York_State_Fallen_Firefighters_Memorial_Roll_of_Honor.csv indicates there are 2549 rows, 5 columns, and the file is 196 KB. The Fire_Department_Directory_for_New_York_State.csv has 1773 rows, 12 columns, and the file is 245 KB.
