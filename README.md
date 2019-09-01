# Houston Housing- Harris County

Updated 08/31/2019

Group Target: Factors to affect house value in Harris county from 2007 to 2017, narrowed to zip codes. Note: For now only able to 2011 to 2017 due to the Census module. Need to find another way to get the rest 4 years.

Main source for all factors:
https://api.census.gov/data/2016/acs/acs1/groups.html
Value of the house categorized to: 26 bins
https://api.census.gov/data/2016/acs/acs1/groups/B25075.html
Need Dataframe of all zip codes from 2007 to 2017 to be saved to a csv file
	Assigned to Nguyen on 08/31/2019. Only able to retrieve info from 2011 to 2017. Need 4 more previous years.

Impacted factors:
1.	Monthly housing costs
https://api.census.gov/data/2016/acs/acs1/groups/B25104.html
Divided to different categories as well
	Assigned to: Nguyen 08/31/2019
	Expected: Dataframe from 2007 to 2017 for all zip codes

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


5.	Crime rate
May go to different API source
6.	Family type
