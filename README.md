# Houston Housing- Harris County
Updated 08/31/2019
Group Target: Factors to affect house value in Harris county from 2007 to 2017, narrowed to zip codes. Note: For now only able to 2011 to 2017 due to the Census module. Need to find another way to get the rest 4 years.
Main source for all factors:
https://api.census.gov/data/2016/acs/acs1/groups.html
Value of the house categorized to:
https://api.census.gov/data/2016/acs/acs1/groups/B25075.html
1.	House value less than 10k
2.	House value 10k-14.9k
3.	From 15k to 19.9k
4.	From 20k to 24.9k
5.	From 25k to 29.9k
6.	From 30k to 34.9k
7.	From 35k to 39.9k
8.	From 40k to 49.9k
9.	From 50k to 59.9k
10.	From 60k to 69.9k
11.	From 70k to 79.9k
12.	From 80k to 89.9k
13.	From 90k to 99.9k
14.	From 100k to 124.9k
15.	From 125k to 149.9k
16.	From 150k to 174.9k
17.	From 175k to 199.9k
18.	From 200k to 249.9k
19.	From 250k to 299.9k
20.	From 300k to 399.9k
21.	From 400k to 499.9k
22.	From 500k to 749.9k
23.	From 750k to 999k
24.	From 1 million to 1.499 mil
25.	From 1.500k to 1.999k
26.	House value more than 2 mil

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
