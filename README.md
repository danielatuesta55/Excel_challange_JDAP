# Excel_Challange_JDAP

## Excel Homework - Kickstart My Chart

### Intention of the Repository

This Repository has been made to summit the homework assignment for my Data Science Bootcamp at Northwestern University

Excel Challange

Student: Jorge Daniel Atuesta

February, 2021

---

### What you will find in this Repository

On the following repository the reader will encounter my solution for the homework assignment. The repository is organized in the following into folders and one README.md file.

The first folder "Excel_Challange_Documents"' contains all the documents created as a solution to the homework by myself.

The second folder will have Images that are related to the readme.md class instructions. You can avoid navigating this folder.

The README.md file (which you are currently reading) has the specification of the assignment as well as the outcome of such. At the end of the file you will see the assignment instructions that where provided by the school. 

---

# Homework Analysis

## Description of the assignment

Using the Excel table that was provided by the school, I had to modify and analyze the data of 4,000 past Kickstarter projects to uncover some market trends.

The first part of the assignment was to use conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

The second part of the assignment was to create a new column O called `Percent Funded` that uses a formula to uncover how much money a campaign made to reach its initial goal.

The third part of the assignment I had to use conditional formatting to fill each cell in the `Percent Funded` column using a three-color scale. Making sure the scale starts at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

The forth part of the assignment I had to create a new column P called `Average Donation` that used a formula to uncover how much each backer for the project paid on average.

The fifth part of the assignment I had to create two new columns, one called `Category` at Q and another called `Sub-Category` at R, which used formulas to split the `Category and Sub-Category` column into two parts.

The sixth part of the assignment I had to create a new sheet with a pivot table that  analyzed the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category**.

The seventh part of the assignment I had to create a stacked column pivot chart that can be filtered by country based on the table you have created.

The eighth part of the assignment I created a new sheet with a pivot table that analyzed the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.

The nineth part of the assignment I created a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

The tenth part of the assignment I created a new column named `Date Created Conversion` that converted the data contained within `launched_at` into Excel's date format.

The eleventh part of the assignment I created a new column named `Date Ended Conversion` that convert the data contained within `deadline` into Excel's date format.

The twelveth part of the assignment I created a new sheet with a pivot table with a column of `state`, rows of `Date Created Conversion`, values based on the count of `state`, and filters based on `parent category` and `Years`.

The thirtennth part of the asignment I created a pivot chart line graph that visualizes this new table.

Finally I created a PDF report that anwsered the following questions:

1. Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create?

This assignment had two possible BOUNS activities that were not enforced but encouraged by staff. For the first bouns activity I had to create a new sheet with 8 columns that had the following values:

* `Goal`
* `Number Successful`
* `Number Failed`
* `Number Canceled`
* `Total Projects`
* `Percentage Successful`
* `Percentage Failed`
* `Percentage Canceled`

Then In the `Goal` column, create 12 rows with the following headers:

* Less than 1000
* 1000 to 4999
* 5000 to 9999
* 10000 to 14999
* 15000 to 19999
* 20000 to 24999
* 25000 to 29999
* 30000 to 34999
* 35000 to 39999
* 40000 to 44999
* 45000 to 49999
* Greater than or equal to 50000

After that I had use the `COUNTIFS()` formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the `Number Successful`, `Number Failed`, and `Number Canceled` columns with this data.

Then add up each of the values in the `Number Successful`, `Number Failed`, and `Number Canceled` columns to populate the `Total Projects` column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

To create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

For the second bouns activity I had to evaluate the number of backers of successful and unsuccessful campaigns by creating **my own** summary statistics table.

In order to accomplish the task I create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns. To create said summary table I did the following:

* Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:
  * The mean number of backers.
  * The median number of backers.
  * The minimum number of backers.
  * The maximum number of backers.
  * The variance of the number of backers.
  * The standard deviation of the number of backers.
* I used the data to determine whether the mean or the median summarizes the data more meaningfully.
* I used the data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?

---

## Outcomes of the project

To display the outcomes of the project I decided to create a PDF file that you can find in the folder Excel_Challange_Documents. You can also find the finished workbook under the same folder. 



---

# References


Kickstarter. (2021, February 17). About Kickstarter. Retrieved from Kickstarter: https://www.kickstarter.com/about?ref=global-footer

Statista. (2020, November 10). Percentage of successfully funded Kickstarted projects as of November 2020. Retrieved from Statista: https://www.statista.com/statistics/235405/kickstarter-project-funding-success rate/#:~:text=This%20statistic%20shows%20the%20share,gone%20into%20successful y%20launched%20projects.

Yeshitla, L. (2017, June 5). Analyzing success rates, failure rates, & trends of Kickstarter and Indiegogo products. Retrieved from medium: https://medium.com/@lydiayeshitla/marketing-research-project-894c0a46c959

**Please note:** ***I am new to README.md files and I don't know how to modify the text so it fits with the APA styleing criteria. ***

---

# Assignment instructions provided by Northwestern Data Science Bootcamp

# Excel Homework: Kickstart My Chart

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

### Before You Begin

1. Create a new space for this project called `excel-challenge` in either DropBox or Google Drive. **Do not add this homework to an existing space**.
2. Store your excel workbooks in here and create a sharable link for submission.

## Instructions

![Kickstarter Table](Excel_Challange_Documents/Images/FullTable.png)

Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

* Use conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

  * Create a new column O called `Percent Funded` that uses a formula to uncover how much money a campaign made to reach its initial goal.
* Use conditional formatting to fill each cell in the `Percent Funded` column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

  * Create a new column P called `Average Donation` that uses a formula to uncover how much each backer for the project paid on average.
  * Create two new columns, one called `Category` at Q and another called `Sub-Category` at R, which use formulas to split the `Category and Sub-Category` column into two parts.

  ![Category Stats](Excel_Challange_Documents/Images/CategoryStats.png)

  * Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category**.
  * Create a stacked column pivot chart that can be filtered by country based on the table you have created.

  ![Subcategory Stats](Excel_Challange_Documents/Images/SubcategoryStats.png)

  * Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.
  * Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.
* The dates stored within the `deadline` and `launched_at` columns use Unix timestamps. Fortunately for us, [there is a formula](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) that can be used to convert these timestamps to a normal date.

  * Create a new column named `Date Created Conversion` that will use [this formula](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) to convert the data contained within `launched_at` into Excel's date format.
  * Create a new column named `Date Ended Conversion` that will use [this formula](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) to convert the data contained within `deadline` into Excel's date format.

  ![Outcomes Based on Launch Date](Excel_Challange_Documents/Images/LaunchDateOutcomes.png)

  * Create a new sheet with a pivot table with a column of `state`, rows of `Date Created Conversion`, values based on the count of `state`, and filters based on `parent category` and `Years`.
  * Now create a pivot chart line graph that visualizes this new table.
* Create a report in Microsoft Word and answer the following questions.

1. Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create?

## Bonus

* Create a new sheet with 8 columns:

  * `Goal`
  * `Number Successful`
  * `Number Failed`
  * `Number Canceled`
  * `Total Projects`
  * `Percentage Successful`
  * `Percentage Failed`
  * `Percentage Canceled`
* In the `Goal` column, create 12 rows with the following headers:

  * Less than 1000
  * 1000 to 4999
  * 5000 to 9999
  * 10000 to 14999
  * 15000 to 19999
  * 20000 to 24999
  * 25000 to 29999
  * 30000 to 34999
  * 35000 to 39999
  * 40000 to 44999
  * 45000 to 49999
  * Greater than or equal to 50000

  ![Goal Outcomes](Excel_Challange_Documents/Images/GoalOutcomes.png)
* Using the `COUNTIFS()` formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the `Number Successful`, `Number Failed`, and `Number Canceled` columns with this data.
* Add up each of the values in the `Number Successful`, `Number Failed`, and `Number Canceled` columns to populate the `Total Projects` column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
* Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

## Bonus Statistical Analysis

If one were to describe a successful crowdfunding campaign, most people would use the number of campaign backers as a metric of success. One of the most efficient ways that data scientists characterize a quantitative metric, such as the number of campaign backers, is by creating a summary statistics table.

For those looking for an additional challenge, you will evaluate the number of backers of successful and unsuccessful campaigns by creating **your own** summary statistics table.

* Create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns.

  ![Images/backers01.png](Excel_Challange_Documents/Images/backers01.png)
* Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:

  * The mean number of backers.
  * The median number of backers.
  * The minimum number of backers.
  * The maximum number of backers.
  * The variance of the number of backers.
  * The standard deviation of the number of backers.
* Use your data to determine whether the mean or the median summarizes the data more meaningfully.
* Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?

## Submission

* To submit your homework, upload the solution and files to a GitHub repo, Dropbox, or Google Drive and submit the link to [https://bootcampspot.com/](https://bootcampspot.com/).

## Employer-Ready Criteria

Students who are marked as employer-ready gain access to our employer referral program, additional workshops, and other resources. Work with your Career Director to become employer-ready. At a minimum, you must have:

- A clear, concise, and compelling resume. Submit via your learning platform for review.
- A polished GitHub profile:
  - 3 - 6 pinned repositories ([instructions here](https://docs.github.com/en/enterprise/2.13/user/articles/pinning-items-to-your-profile))
  - at least 5 commits per repository
  - professional titles, i.e. not "Homework #1"
  - thorough README.md files for each repository
  - clean code

---

© 2019 Trilogy Education Services
