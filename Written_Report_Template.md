# Kickstarting with Excel

![Fever Funding Analysis](https://guiauniversitaria.mx/en-el-dia-mundial-del-teatro-las-10-obras-de-teatro-mas-exitosas-de-la-historia/)

## Overview of Project

The main objective of this report is to analysis play funding in UK, in order of detecting the best moment and goal amount to launch Fever fund raising.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date: 

The goal of this analysis is to learn about the best and worse moments to launch the fund raising campaign. To make this analysis is very important to be aware of the filters that we have to implement. 

![Analysis of Outcomes Based on Launch Date](https://github.com/FernandoLaguna/kickstarteranalysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals: 
The main objective of this analysis is to learn if there is a realtion between the goal settled on the campaign and the final outcome. In this analysis the first tngo that we have to do is to determine ranges og goal amounts and then build a table with data and finally a chart to visualize the information. 

![Analysis of Outcomes Based on Goals](https://github.com/FernandoLaguna/kickstarteranalysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties
-For the Analysis of Outcomes Based on Launch Date the main challenge was applying filters to delete "live" from colums and joining all the months
-Regarding the Analysis of Outcomes Based on Goals I learned a new Excel formula `=COUNTIFS)`. The most important challenge that I found was to chang some variables each column and row to build the table. I couldn´t find an Excel function to atomaticaly change a letter or a number inside a formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - In order to be successful in funding the play I would recommend Luisa to launch her campaingn in May or June.
  - She must avoid launching her campaign in December.

- What can you conclude about the Outcomes based on Goals?
  - My recommendation is to set a goal on one of this two ranges
    - From 35,000 to 45,000
    - Less than 5,000

- What are some limitations of this dataset?
  - There are other factors that could be realted to the success of the campaign such as the genre of the play, the script, the casting, etc. 

- What are some other possible tables and/or graphs that we could create?
  - I would create a graph by month but open by year. The objetive would be to detect possible differences in each year that could affect the monthly result that we already obtained.
  - A graph Play Outcomes by launch date (it would more accurate due to Luisa is planning to produce a play)
  
