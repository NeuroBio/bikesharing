# Bikesharing: a pitch to open a bike sharing company in Des Moines

## Overview
Bike sharing is a successful service in New York city and may also make for a profitable business in Des Moines.  The linked to Tableau document displays information about usage of bikes in New York city to convince potential investors that this business model will be feasible in Des Moines.

## Results
### Resources
[Original Data](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)

### Analysis
The data linked to above was downloaded and used as is with two exceptions.  1) The tripduration column was provided as an integer.  A python script was used to convert this column into datetime format.  2) The gender column was provided as an integer, where 0 = unknown, 1 = male, and 2 = female.  A Tableau calculated field converting the numbers to their corresponding string value as described above was used to create the gender strings column.  All figures were made using Tableau.

### Tableau Link
[Tableau Viz](https://public.tableau.com/views/Module14ChallengeBikeShareViability/BikeShareViability?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Figures
![Fig-1](resources/peak_august_hours.png)

**Figure 1:**

![Fig-2](resources/checkout_time_for_users.png)

**Figure 2:**


![Fig-3](resources/checkout_time_by_gender.png)

**Figure 3:**


![Fig-4](resources/trips_by_weekday_hour.png)

**Figure 4:**


![Fig-5](resources/trips_by_gender_weekday_hour.png)

**Figure 5:**


![Fig-6](resources/user_trips_by_gender_weekday.png)

**Figure 6:**


![Fig-7](resources/gender_breakdown.png)

**Figure 7:**


![Fig-8](resources/gender_usertype_breakdown.png)

**Figure 8:**


## Summary

### This Analysis

### For the Future
