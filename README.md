# Data Wrangling Final Project
> The goal of this project is to examine the relationship between a college student’s academic and personal information and their salary statistics. Our research questions are as follows: 

> - What are the important summary statistics regarding the salary information for the Big 10 schools? 

> - Which Big 10 school has the largest median student debt? 

> - Is there a correlation between starting salary and average student debt? 

> - Do Midwest and Non-Midwest schools have different median starting salaries? 

## Table of Contents
* [General Info](#general-information)
* [Technologies and Languages Used](#technologies-and-languages-used)
* [Features](#features)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
All university students have thought about and continue to think about our future post-graduation. Whether this is the salary we hope to receive, the job title, or even other details such as the location of where we would prefer to work. The concerns of post-university graduation life begin well before even starting at a university. Given this, we have decided to analyze what factors contribute to the different median post-graduation salaries. We have decided to narrow our scope down to the 14 universities in the Big Ten Conference, including the University of Iowa. Overall, we will be looking for the significance of the following factors contributing to the universities' median post-graduation salaries; admission rate, the average SAT score, the median post-graduation debt, the average and median family income, in-state tuition and fees, and out-of-state tuition and fees. We will use data from the Wall Street Journal and Open Data Platform to investigate different statistics of universities from the Big Ten conference. 

## Technologies and Languages Used
- R
- Microsoft Excel


## Features
**Data:**
- Wall Street Journal Data 
  -The first data source we will be using is from the Wall Street Journal1 with statistics about the starting median salaries and mid-career median salaries for graduates of the different universities across the U.S. We plan to scrape the website using R-Studio and obtain a subset of the data only including universities from the Big Ten Conference. There are 320 colleges in the original dataset with 8 columns pertaining to the college, the region of the college, and salary information. 

- US Department of Education College Data 
  -The second data source is an existing dataset from the U.S. Department of Education College Scorecard2. The College Scorecard data source from 2015 includes 7,667 rows of universities and 2,392 columns of statistics. We plan to analyze a subset of the data only including universities from the Big Ten Conference and the admission rate, the average SAT score, the median post-graduation debt, the average and median family income, in-state tuition and fees, and out-of-state tuition and fees for each of these universities. We now have 14 columns and 14 rows in our cleaned set. 
  
- Integration of the two datasets 
  -Given that the two data sets contained a similar column with the college name in mind, we utilized a horizontal integration to integrate both, adding in the salary information for each Big 10 school. 
  
## Project Status
**Project is:** Complete. 

**Conclusion:** 
  Our project incorporated data from the Wall Street Journal (WSJ) and the US Department of Education (USDE). WSJ data included primarily salary-specific information about hundreds of universities and colleges throughout the US. In contrast, USDE incorporated more personalized information regarding student debts, family income, and other significant information universities collect about students. We chose to focus specifically on the Big 10 Universities, given that we are students at the University of Iowa. We chose to perform 4 different analyses with the given data in order to provide insight on the salary statistics of the schools, the average debt of the university students, the debt versus the starting salary, and significance of school location for salaries. In doing so, we utilized summary tables, map visualizations, linear regression, and a t-test for significance.  

  Through our findings, we were able to better understand the salary make-up of typical Big 10 university students, both fresh out of college, and mid-way through their careers. The numbers were relatively different at different levels of career progression which we found to be interesting. A map visualization aided in getting a better sense of both where the Big 10 universities were located, but also how the average debt of those university students varies quite drastically. It might have been simple to hypothesize that the more expensive a school is, the more prestige it will be, and the starting salary will be higher but through the linear regression, we found that there is not real statistically significant correlation with the amount of debt a student incurs. We believe this is probably because each student’s situation is different, and it the cost of a school doesn’t determine what kind of jobs students are able to obtain. Our final test was used to answer our question of geographical location impact on salary but ultimately allowed us to conclude that the location of the school, Midwest vs. Non-Midwest, does not play a statistically significant role in determining salary. 

## Room for Improvement

There are a few limitations to this project which we discovered as we progressed through it. For instance, given that we are using such a small and broad dataset (Only Big 10 Schools and no salary adjustments by major, skills, etc.), this limits the scope of our findings. The location may not play a role in salary for these instances, but this conclusion cannot be applied to schools outside of the dataset. Furthermore, this data may not give an accurate representation of the current market trends both due to COVID and just standard inflation so the salaries may not be up to date. We could continue this study on a larger dataset which includes a different conference of universities, different physical locations of universities such as east and west coast, or even try to apply the same functions with every university in the United States. In doing the entire US, we could get very good idea of salary information and if location impacts it or not. We could also consider examining some other factors such as more information tailored to a student’s family life given that there were some features including this. We could analyze questions about whether or not the family income plays a role in a student’s debt or also look at a sort of salary comparison between family and student. Overall, there are many avenues we could take the dataset, but we believe we chose some very interesting variables to utilize and manipulate.  

## Acknowledgements
**Data Source:** 
  Wall Street Journal Data & US Department of Education College Data 
**Project Team:**
Hannah Baucom, Nick Biancuzzo, Vincent Parcelli, and Zak Zahner 

## Contact
Created by Hannah Baucom, Nick Biancuzzo, Vincent Parcelli, and Zak Zahner - feel free to [contact me](hannahbaucom11@gmail.com)!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
