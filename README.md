# Houston Housing- Harris County

Updated 09/02:

Group Target: Factors to affect house value in Harris county from 2007 to 2017, narrowed to zip codes. Note: For now only able to 2011 to 2017 due to the Census module. Need to find another way to get the rest 4 years.

Main source for all factors:
https://api.census.gov/data/2016/acs/acs1/groups.html

Impacted factors:
1.	Monthly housing costs
https://api.census.gov/data/2016/acs/acs1/groups/B25104.html
Divided to different categories as well
	Assigned to: Nguyen 08/31/2019
	Expected: Dataframe from 2007 to 2017 for all zip codes
	Done by Nguyen 09/02/2019

2.	Income
https://api.census.gov/data/2016/acs/acs1/groups/B19013.html
Look for median income and some other income categories
	Assigned to: Patrik 08/31/19
	Expected: Dataframe from 2007 to 2017 for all zip codes

3.	Population
Look for other population factor like gender or generation as well
	Assigned to: Suleyman
	Expected: Dataframe from 2007 to 2017 for all zip codes

4.	Education
Look at enrollment data
https://api.census.gov/data/2016/acs/acs1/groups/B14001.html
Also look at educational attainment meaning the degrees they hold
	Done by Nguyen 09/01/2019

5.	Crime rate
May go to different API source

6.	Employment status
	Assigned to Patrik 09/02/2019

7.	Household types
https://api.census.gov/data/2016/acs/acs1/groups/B11001.html
	Assigned to Eva 09/02/2019

8.	Travel time to work
https://api.census.gov/data/2016/acs/acs1/groups/B08303.html
https://api.census.gov/data/2016/acs/acs1/groups/B08135.html
	TBD

9.	Poverty
https://api.census.gov/data/2016/acs/acs1/groups/B07012.html

