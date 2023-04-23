# Analysis of Olympics: Athlete events and effects of socio-economic events
This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on.

### Dataset
The dataset includes information about 271,117 athletes who have participated in the Olympics from 1896 to 2016. The dataset has been taken from R4DS Tidy Tuesday’s challenges for the year 2021 in github.com (https://github.com/rfordatascience/tidytuesday/tree/master/data/2021/2021-07-27) inspired by the articles from Financial Times and FiveThirtyEight which tried to analyze the countries which over – performed or under – performed their set expectations. 
It has two datasets:

1. athlete_events

This file contains information on every athlete and their performance at each Olympic Games, including their name, country, sport, event, and medal won (if any).

![image](https://user-images.githubusercontent.com/59004632/233839734-7fae9ada-a2e9-4366-b3cb-b1eaed5c2f9f.png)

2.noc_regions

This file contains information on the National Olympic Committees (NOCs) and their respective regions.

![image](https://user-images.githubusercontent.com/59004632/233839777-1ce40a08-ac0b-4e13-8e5c-b618c305def3.png)

### Data Cleaning
The original dataset required some cleaning to remove missing and duplicate values, and merge the data into a single file. This was done using R and the tidyverse library.

### Data Analysis
-will be performing an analysis to study the trends around 
  1. participation and distribution of medals across various age groups, 
  2. check for some interesting outliers and 
  3. check how certain socio-economic/international events might have effected the Olympics.
  
-used R programming to support my analysis and generate reports with aesthetic and visually appealing graphs that can even be understood by a layman.
