# EDA-Clubhouse

* Investigating users with highest number of followers on social media apps.
* Data is present as a sql table and not a csv file, therefore, creating a connection and reading the sql data and then creating a Dataframe from it.
* Dataset contains 13,00,515 rows and 10 columns.
* Analyzing numers present for different social media apps to come up who leads on several platforms.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, Matplotlib, missingno, plotly, seaborn, and sqlite3.
.

## Data Used
**Data Source**:https://www.kaggle.com/fahadmehfoooz/clubhouse-eda/data
This file is a sqlite database. It contains a table named user whose columns are :

user_id
name
photo_url
username
twitter
Instagram
num_followers
num_following
time_created
invitedbyuser_profile

## Data Wrangling 
*  Dropped columns with high null values.
* Plotting barplots, pie charts, etc.

Some of the visualizations are shown here:

![alt text](https://github.com/fahadmehfooz/EDA-Clubhouse/blob/main/images/__results___22_1.png)

# Conclusion:

* Highest missing values for twitter, followed by Instagram.
* Rohan Seth has the highest number of followers.
* Number of people who use instagram are higher.
* 63.8 % people do not use any social media applications and 36.2 % people use both social media applications.




