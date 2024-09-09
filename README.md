# Power-BI-Project

### Project Overview 
In this project, real-life data from a survey will be cleaned and then a dashboard will be created showing various visualizations. 

### Data Sources

Survey results are used to source the data for the visualizations. These results are given in an excel spreadsheet and imported into Power BI.
The survey investigates individuals in the data profession and provides information on various career topics. 


### Tools

- Excel - Used to gather the data
- Power BI - Data cleaning and visualization 

### Data Cleaning 
In the initial data preparation phase, we performed the following tasks: 
1. Data loading and inspection.
2. Removal of unnecessary columns.
3. Standardization of data.
4. Converting columns into a more useable format.

### Creation of Dashboard
After cleaning the data a dashboard was created, showcasing the visualizations. The dashboard can be viewed below. 

<img width="995" alt="Screenshot 2024-09-09 at 12 15 16" src="https://github.com/user-attachments/assets/5d6a4cea-617f-4f7a-9c9f-773b6d6b827f">

#### Cards
Two cards were created at the top right-hand side of the dashboard. These show the total count of survey participants and the average age of participants. 

#### Bar Chart
A bar chart was created which shows the average salary of individuals based on their job titles.

#### Stacked Column Chart 
This visualization was used to show participants' favourite coding language and further filtered the results by job title.

#### Treemap
The treemap shows the country demographic of participants which can be useful when considering factors such as salary, which can be affected by geographical location. E.g. For average salary this can be broken down by country as different countries have different costs of living and therefore will have differences in average salary. 

#### Donut Chart
This chart shows how difficult it was for participants to break into the data field on a scale from 'Very Easy' to 'Very Difficult'.

#### Gauge Charts 
Two gauge charts were created to show participants happiness in relation to their work/life balance and their salary. Happiness was rated on a scale of 1 - 10. 

### Key Insights
1. The majority of participants were from the United States.
2. Python is the most popular programming language follwed by R.
3. The majority of participants were data scientists.
4. Most participants found it neither easy or difficult to break into the data profession.
5. Average happiness with work/life balance is 5.74, meaning on average, participants are only slightly happy with their work/life balance.
6. Average happiness with salary is 4.27, meaning on average, participants are slightly unhappy with their salary.

### Limitations
Since data was cleaned on Power BI, this limtied the potential of data cleaning. This is evident in the visualizations where the catagory 'Other' is quite large due to a lack of standardisation when cleaning the data. To solve this issue, the data could be cleaned in MySQL or Excel.

### References 
1. [Dataset](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbFkya1VIM0REUHdOWVF3OE53eEtkMVowR09TZ3xBQ3Jtc0ttb214b0NaZHUyUFNleGNUdW1Sb2RvYUhrRm1HUi0zQjdBZHBFNkJma2Noc0ZtX0JHVUJSZzZMNlFfSGlEcnhLZDdZLXNTNzZibmc0ZlkyMUdkRl9uUE9QTjRRWGMxcTdnbnNkbUp1bDh4SlRwaXVOdw&q=https%3A%2F%2Fgithub.com%2FAlexTheAnalyst%2FPower-BI%2Fblob%2Fmain%2FPower%2520BI%2520-%2520Final%2520Project.xlsx&v=pixlHHe_lNQ)




