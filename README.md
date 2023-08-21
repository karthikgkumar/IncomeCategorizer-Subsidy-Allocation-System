# IncomeCategorizer-Subsidy-Allocation-System
Developed an income classifier system capable of accurately categorizing individuals based on their income levels.

## Problem Statement 
<strong>Subsidy Inc.</strong> is faced with the challenge of accurately determining the income of individuals in order to deliver subsidies. Obtaining precise income data is a complex task worldwide. However, Subsidy Inc. has acquired a substantial dataset comprising authenticated information on individual income, demographic factors, and select financial parameters.
<br/>
To address this issue, Subsidy Inc. aims to develop an <strong> income classifier system </strong>capable of accurately categorizing individuals based on their income levels. This system will leverage the available dataset to make reliable predictions and enable the efficient delivery of subsidies to those who qualify.
<br/>
By developing an effective income classifier system, Subsidy Inc. aims to enhance the accuracy and efficiency of their subsidy allocation process. This will empower them to allocate subsidies more equitably and ensure that individuals receive the appropriate financial assistance based on their income levels 
## About Dataset
Inspiration from https://archive.ics.uci.edu/dataset/20/census+income.
Predict whether income exceeds $50K/yr based on census data. Also known as Adult dataset.
|Variables|Data Type| Description | Categories of variables |
|---------|----------|------------|-------------------------|
|age      |integer   |The age of individual in years| __    |
|JobType  |string    |Working status of a person, which sector does he work on|Federal-gov,Local-gov & 6 more|
|EdType   |string    |The level of edcation|10th, Masters & 14 more|
|maritalstatus|string|The marital status of the individual|Divorced,Never-married & 5 more|
|occupation|string|The type of work the inddividual does|Armed-Forces,Sales & 12 more|
|relationship|string|Relationship of individual to his/her household|Husband,wife & 4 more|
|race      |string   |The individual's race     | Black, White & 3 more|
|gender    |string   |The individual's gender   |Male,Female|
|capitalgain|integer | The capital gains of the individual(from selling an asset such as stock or bond for less than the original purchase price )|__|
|capitalloss|integer |The capital losses of the individual (from selling an asset such as a stock or bond for less than the purchase price)|__|
|hoursperweek|integer|The number of hours the individual works per week|__|
|nativecountry|string|The native country of an individual|United-States,Canada & 40 more|
|salstat    |string  |The outcome variable indicating whether a person's salary status|less than or equal to 50,000, greater than 50,000|

# Conclusion
The dataset was pre-processed and analyzed to remove redundant attributes. Then,classifiers like Logistic Regression and K-Nearest Neighbour were experimented for the task of predicting the **Salary Status**. The experimental results show that the **Logistic Regression model** achieved the highest accuracy of **84.98%**. Whereas, the **K-Nearest Neighbour classifier** had an accuracy of **82.94%**
