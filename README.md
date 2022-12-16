# bellabeat
Data analysis of a pet project from Google Course
# 1. Ask
Business task: Analyze Fitbit data to gain insight and help guide marketing strategy for Bellabeat.

Primary stakeholders: Urška Sršen - Bellabeat’s cofounder and Chief Creative Officer and Sando Mur - Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
Secondary stakeholders: Bellabeat marketing analytics team.

# 2. Prepare
Dataset: https://www.kaggle.com/datasets/arashnic/fitbit 
There are 33 total participants who provided the data of using the Fitbit technologies.
Data has 18 csv files containing different information about usage of devices.
Each file represents a separeted set of data in a wide form.

As it was stated earlier there are only 33 users which might be not enough for a thorough analysis. 

# 3. Process
Tools were used: Google Spreadsheets, SQL and Tableau. There are 18 csv files. Some of them are relatively small, so it made sense to use Spreadsheets in these cases. Other files were larger and SQL was used to go through them. 
Checked data format. All data is correct.
Checked ids to be more or equal to 0. All data is correct.
Data format in some files was changed to correct format YYYY-MM-DD. 
No errors were found.
Additional files were created in order to separate important data for analysis. For example, in files dailyIntensities_merged and dailyActivity_merged. 

# 4. Analyze
According to provided data there are 4 levels of activity: Fairly Active, Lightly Active, Sedentary Active and Very Active. 
The data let us discover that the most of the time people are Sedentary Active with a huge advantage: 991.2 average minutes against 192.8 which is lightly active (the second place).
But the distance covered as Sedentary Active is the lowest - about 0.002 average which is almost nothing compared to 3.341 as Lightly Active which is in the first place.
Unfortunately the data provided doesn't specify what metric is used to measure the distance. We can only assume it is in km.

People tend to spend more time in bed and sleep on Sundays followed by decrease on Mondays. Time spent in bed and asleep is about the same during the work days.

Also the data showed when people are most active and inactive during a day based on calories spent. Most calories spent are usually in the evening: 6pm, 5pm and 7pm. Besides that 12pm and 1pm are also very active. The most calm time is during the night: from 11pm till 5am. The most active time is twice as big as the inactive.

8 people provided data about their BMI - Body Mass Index. According to Centers for Disease Control and Prevention (https://www.cdc.gov/healthyweight/assessing/index.html) if BMI is 18.5 to 24.9, it falls within the normal or Healthy Weight range. 25.0 to 29.9, it falls within the overweight range. And if BMI is 30.0 or higher, it falls within the obese range. 
In the dataset 3 out of 8 people fall into normal or Healthy Weight range. 4 people fall within the overweight range. And 1 person is within the obese range.

# 5. Share
Every finding above was presented via Tableau
[Average Minutes of Activity split by Intensity](https://public.tableau.com/app/profile/albert.akopian/viz/AverageMinutesofActivitysplitbyIntensity/Sheet1)
[Average Activity Distance split by Intensity](https://public.tableau.com/app/profile/albert.akopian/viz/AverageActivityDistancesplitbyIntensity/Sheet1)
[Average minutes spent in bed and asleep](https://public.tableau.com/app/profile/albert.akopian/viz/Averageminutesspentinbedandasleep/Sheet1)
[Average colories by hour](https://public.tableau.com/app/profile/albert.akopian/viz/Averagecoloriesbyhour/Sheet1)
[Average BMI per person](https://public.tableau.com/app/profile/albert.akopian/viz/AverageBMIperperson/Sheet1)

# 6. Act 
Conclusion based on our analysis:

*Sedentary has the most significant portion of activity. This level takes aberage about half of a day.
*Most users sleep and spend time in bed the most on Sundays. 
*People are most active in lunch time and in the evening. An assumption is that people are most likely to take a break at work and leave work in these periods of time.
*There are different level of BMI amongst people. With the provided data we can assume that the most of users are in overweight range.

For marketing team:
*The marketing team can make ads focused on encouraging people do more exercises on the weekends and to be more active either before work in the morning or after around 8pm. 
*Also encourage people to be more active in theire active time to not be in the sedentery level of activity. 
*Other option is to provide information about exercises and diets for people with overweight, beacause most of the users are in this range.
