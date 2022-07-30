# visualization
The Exploratory Visualization of the 120 years of olympic games held between 1896 and 2016.
The main aim is to show the readers the overview of the olympic games like the no of events over the years,Athlete participation,Medal count,Male and Female participation,Age,Height and Weight distribution of the athletes.

## Data Source
The data is downloaded from this kaggle link: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results. This dataset was created by rgriffin in May 2018.

## Dataset

The dataset consists of 5 numerical variables: ID represented by a unique number for each athlete, age, weight, height, and year. Height is presented in centimeters and weight in kilograms.

The remaining variables are of a type character. They include:

1. Name (Athlete’s name)
2. Sex (M or F)
3. Team (name of the team, mostly it’s a country but sometimes it is a country with a number or an old name such as “East Germany”)
4. NOC (National Olympic Committee 3-letter code, more uniform way of referring to a team)
5. Games (Year and season)
6. Season (winter or summer)
7. City (where the Games have been hosted)
8. Sport (name of the discipline)
9. Event (subcategory - for example running will be divided by distance)
10. Medal (Gold, Silver, Bronze, or NA)

![dataset](https://user-images.githubusercontent.com/95603389/181918399-ab332cc5-e17f-4a0a-95ea-a1e23a4f0fae.png)

## Libraries used in this project
- dplyr
- ggplot2
- gganimate
- plotly
- RColorBrewer

## PLOTS
This visualisation projects contains _ plots and 2 Animated plots:

#### Number of Athletes participated,Nations participated and Events occured over the time period

![Rplot](https://user-images.githubusercontent.com/95603389/181924867-f3243092-b5a2-4322-a2e3-b2ec62f12367.png)

#### Participation of Male and Female Athletes over the time period

![file7b1c2a8a7739](https://user-images.githubusercontent.com/95603389/181925053-7a47b7a8-e374-4485-84a5-eb98bfbf7102.gif)

#### Top 30 Nations in order of medal count

![Rplot01](https://user-images.githubusercontent.com/95603389/181924987-caecffb9-172c-46bf-8f08-7beb46511cc0.png)
 
#### Medal count of Nations over the time period

![image](https://user-images.githubusercontent.com/95603389/181925170-ee2ea56b-91f6-4992-97a3-17985bf0a917.png)


