# Kickstarter Analysis

## Overview of Project
* A deep-dive analysis that highlights key metrics and trends that provide insight, both visually and graphically, to guide decision-making for Kickstarter Campaigns

### Purpose
* Identify, highlight, and investigate what factors drive successful Kickstarter campaigns and how this can be a benchmark for future successful Kickstarter Campaigns such as Louise's Production Project: ***Fever*** 


## Analysis and Challenges
* This exploratory data analysis was performed on thousands of previous crowdfunding projects to highlight key metrics such as outcomes based on various factors such as funding goals, timelines, budgets, type of campaigns. 
* By taking the data set and using conditonal formatting and filters we can create pivot tables and pivot charts the highlight specific data that answers niche questions about these campaigns.  
* To do this I started with taking the data set and homogenizing it by freezing panes, applying filters and color coding the outcomes for successful, failed cancelled or live campaigns. After, creating new columns I created one for Years to see how each category has done over a yearly period. Taking the date conversion we created using Unix time stamp converters, we're able to focus on the years of these projects by using the Year( ) Function. 
* Once this has been done we take a Pivot Table using Years and Parent Category to see the outcome of all categories over a yearly period 
![Pivot Table for Outcomes by Launch Date](https://github.com/RichardH395/repo-kickstarter-analysis/blob/main/Pivot%20Table%20for%20Outcomes%20by%20Launch%20Date.png)
* We can visualize this to show the outcomes of all categories that show how theatre is a very popular category: 
![Parent Category Outcomes](https://github.com/RichardH395/repo-kickstarter-analysis/blob/main/Parent%20Category%20Outcomes%20.png) 
* As we can clearly see, Theatre is a popular category. Following up on this we filter categories to look at Theatre specifically to see a more detailed explanation regarding to Louise's question of how Launch dates affect these outcomes. We can take the pivot table and filter for theatre.
* ![Pivot Table for Theatre Outcomes by Launch Date](https://github.com/RichardH395/repo-kickstarter-analysis/blob/main/Pivot%20Table%20for%20Theatre%20Outcomes%20by%20Launch%20Date%20.png) 
#### Continuing Further
* Now that we have the data showing how outcomes are affected by launch date for Theatres, we create a pivot chart to better visualize this trend:
![Outcomes Based on Launch Date](https://github.com/RichardH395/repo-kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Launch%20Date%20.png)
This is our first Deliverable, now we have a line chart with markers that show the outcome of the theatre category. We can see that May and June are popular launch dates for successful campaigns. 

### 



### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
