# The excel_challenge

# Background 
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organisations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organise and analyse a database of 4,000 past projects in order to uncover any hidden trends.

# Proposed solution
Re-saved the data to avoid data loss and created a shareable link with regular uploads to keep the data secure. Conditionally formatted the (state & percent_funded) columns with diffrent colors to associate successful, failed and canceled campaigns.  

<img width="1194" alt="main-worksheet" src="https://user-images.githubusercontent.com/104544617/167882592-9bba87b2-b827-4884-8281-706056554e3b.png">
The percent_funded column was created to determine the funds were raised to reached its targeted goal of the campaign. additionally, average-donantion column was intended to show how much each campaign backer paid on average. Also, two new columns Category and Sub-category was created by splitting (Category & Sub-category) column. This step is important in cleanind the data and will be useful in the next steps. 

# Pivot tables and charts
![image](https://user-images.githubusercontent.com/104544617/167884703-540d198c-4143-4f7d-a397-2b81f77a8543.png)
Stacked column bar chart shown can be filtered by country/region using the pivot table shown. The essence of this p.table and chart was to uncover the categories trend/perfomance based on their successful, failed or canceled campaign. 
![image](https://user-images.githubusercontent.com/104544617/167886042-97f79380-8665-46ff-84c4-ff7792cd776f.png)
column bar chart shown can be filtered by country/region and category using the pivot table shown. The aim for this p.table and chart was to showcase the sub-categories trend/perfomance based on their successful, failed or canceled campaign. 

