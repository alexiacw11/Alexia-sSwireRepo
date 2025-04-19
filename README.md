# AlexiaSwireRepo
Code for University of Utah's MSBA Capstone Competition.

## Business Problem
Swire Coca-Cola is a leading tech company that puts clients at the center of their work. As a bottler and distributor throughout 13 Western states, operational efficiency is a necessity to remain successful and create long-term relationships with clientele. Swire Coca-Cola must avoid prematurely moving high-growth potential customers to white truck delivery (Alternate Route to Market) as this could severely impact revenue growth. The purpose of this project is to reasonably maximize sales by predicting which clients have the potential to reach the high-performing SCCU optimal threshold of *** gallons annually.

## Project Objectives
<ul>
<li>Detailed report of EDA findings and model predictions
<li>GitHub repository, including code and README files
<li>Visually appealing slide deck that clearly conveys project findings
</ul>

## Business Value of the Solution
The benefits of predicting high-growth profile accounts are as follows.
<ul>
<li>The company can optimize operational efficiency by prioritizing crucial delivery routes while reducing delivery costs. 
<li>Future revenue can be safeguarded with maximized sales.
<li>Contact with customers can be maintained as Swire Coca-Cola assists them through curated consulting services that propel the success of their business. 
</ul>

## Personal Contribution to the Project
<ul>
<li> Discovered the presence of multicollinearity in the data
<li>Models <ul>
  <li> 2023 linear Regression and interpretation
  <li> 2024 linear regression and interpretation 
<li> Predictive analytics and appendix slides of the presentation 
<li> Answered Swire Coca-Cola's modeling questions post-presentation </ul>

## Difficulties Encountered Along the Way
1. Data Quality: Some information from data columns was redacted for privacy purposes, for instance, zip codes. This made it slightly more difficult to interpret our results and how it pertained to the company's mission. Additionally, some improvements could be made by Swire Coca-Cola to support further the analysis of fulfillment rates, delivery efficiency, and customer behavior. 
2. Multicollinearity: This can inflate the variance of coefficient estimates, making the model sensitive to small changes in the data and potentially reducing interpretability. I had to do my best to remove this from our model. 
3. Potential Outliers and Noise: Some numerical features contained extreme values that were potentially outliers or data entry errors. These values can distort model training, especially in distance-based or sensitive algorithms, necessitating careful inspection and possible transformation or filtering.
4. Deciding Solution Approach: There were many ways to address the questions posed by Swire Coca-Cola, but as a group we wanted to be consistent with our approach - either go all in on BlackBox methods or commit to traditional models. Ultimately, we decided on the latter.
5. Time Constraints: While I had plenty of ideas throughout the modeling process, I could not try all of them because of time constraints. This is an "unfortunate" reality that mimics what I will experience in the real world. 

## Solution
<ul>
<li>The best performing was a regression model that I created 
<li>The model predicts the volume of units ordered, using total_units_ordered as the response variable
<li>Trained on 2023 data and tested on two test sets, 2023 and the full 2024 dataset 
<li>Test 2023: <ul>
<li>Adjusted R-squared 0.6
<li>R-squared 0.56
<li>RMSE is 81.90</ul>
<li>Test 2024: <ul>
<li>R-squared 0.57 
<li>RMSE is 92.6</ul>
<li>Computation Time: Using a high-capacity server, the final model took 2.20 hours to train and make predictions.
</ul>

## What I learned
<ul>
<li> Company data has the potential to be messy, so it is important to pay attention
<li> Communicate with the company if more data is needed/would be beneficial
<li> The importance of approaching a business problem creatively 
<li> Performance vs. Interpretability Tradeoff in regards to the modeling process 
<li> Be open to critiques and suggestions 
<li> There is no "right way" to complete a data science project, but you must be able to defend and clearly explain your process
</ul>

