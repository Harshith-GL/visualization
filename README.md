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

### Number of Athletes participated,Nations participated and Events occured over the time period

![Rplot](https://user-images.githubusercontent.com/95603389/181924867-f3243092-b5a2-4322-a2e3-b2ec62f12367.png)

### Participation of Male and Female Athletes over the time period

![file7b1c2a8a7739](https://user-images.githubusercontent.com/95603389/181925053-7a47b7a8-e374-4485-84a5-eb98bfbf7102.gif)

### Age distribution of the athletes

![Rplot04](https://user-images.githubusercontent.com/95603389/181925508-2bbdabd6-f191-4fda-a71c-b22c0c7c5ef1.png)

### Height distribution of the athletes

![Rplot07](https://user-images.githubusercontent.com/95603389/181925530-66a61f86-6134-40f8-b5c2-f8b0e5412d45.png)

### Weight distribution of the athletes

![Rplot05](https://user-images.githubusercontent.com/95603389/181925523-1e866942-2eff-4a35-b272-bf43468170f8.png)

### Average weights for summer and winter sports

![b52331be-f72d-44de-82a5-9f4ac9d2d5cb](https://user-images.githubusercontent.com/95603389/181925958-ee689a4d-4f80-4a71-bea7-dd8006a1d027.png)

### Average Heights for summer and winter sports

![0e596d27-f665-4aed-9d31-99ea86691668](https://user-images.githubusercontent.com/95603389/181925949-d5b4c739-5ea8-47e3-b68b-8d8930d8fa03.png)

### Top 30 Nations in order of medal count

![Rplot01](https://user-images.githubusercontent.com/95603389/181924987-caecffb9-172c-46bf-8f08-7beb46511cc0.png)
 
### Medal count of Nations over the time period

![file132c706271f2](https://user-images.githubusercontent.com/95603389/181925230-ee61434c-fd68-470f-ba0a-df046771f676.gif)

### Map of Nations with the medal count

![Rplot02](https://user-images.githubusercontent.com/95603389/181925319-f8a1a97e-8130-4448-a89b-6527e87eaf21.png)

### Medal Count of INDIA

![Rplot03](https://user-images.githubusercontent.com/95603389/181925364-596de492-5200-4aa2-aa75-9df2b560f107.png)



