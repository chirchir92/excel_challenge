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
![image](https://user-images.githubusercontent.com/104544617/167886697-55091d7e-6575-46a7-af52-816913a4c678.png)
The main worksheet saved in unix timestamp was converted to gregorian calendar format dates. Pivot chart line graph was created using the converted dates, state and parent category to uncover trends of the successful, failed and canceled campaigns.

# Bonus
![image](https://user-images.githubusercontent.com/104544617/167888243-adaab0a2-faca-4b1e-8e27-04c236e26084.png)
COUNTIFS() formula was used to show how many projects whether (successful, failed or canceled) were launched within each range shown in the table (see excel workbook). Using the total the percentages of each categories were calculated in their respective goal range.

# Statistical analysis
The mean and median of the two dataset(successful&failed) DO NOT summarise the data more meaningfuly. For successful, the mean is larger than the median by a great margin, therefore, this shows that there are more successful backers than they are not. Thus, the mean is most indicative of the data and gives a better position or location of the distribution.  The same is true for failed outcomes. But ideally, in this case to determine the appropriate statistic to represent the data we would consider the data rather than the context that is intended to inform. 

<img width="433" alt="Screen Shot 2022-05-12 at 1 39 25 am" src="https://user-images.githubusercontent.com/104544617/167890896-3210a2e2-b8fa-412f-b574-776543f1ff92.png">

We have calculated mean and median  of the data, these central tendecies measure are important in calculating the variability of the data. The successful and failed backers count have high variability. The data have a very high spread that is evident from range, variance and standard deviation.  This makes sense becasue we can we use the measures of central tendencies and dispersion to check the variabity.


