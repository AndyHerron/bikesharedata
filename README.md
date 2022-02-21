# NYC CitiBike analysis

## Overview of analysis
CitiBike is a large company that operates a bikesharing system in New York.  We were asked to analyse their ride data from August 2019 and see if that might be applicable to starting a similar bike sharing service in different communities.

### Resources
* Data Sources: 201908-citibike_tripdata.csv -> then converted to CitiBikeData.csv
* Software: Python, Jupyter Notebook, Tableau

## GitHub has disabled LFS for my account due to the fact that I have exceeded my data storage limit. 
### I have added "*.csv" to my .gitignore file, so my datafiles are not uploaded to my GitHub page.
### You can see that I converted the file correctly in the Jupyter Notebook file, and the charts on Tableau work correctly.

## Results
[link to my story on Tableau](https://public.tableau.com/app/profile/andy.herron/viz/CitiBikeData_16453405912060/CityBikeDatastory?publish=yes)

### Tableau visualizations

1. This shows the length of time (trip duration) for the bike rentals.
![Checkout Times for Users](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_1.png)
 
2. Similar to the first chart, but broken out by gender of user.
![Checkout Times By Gender](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_2.png)

3. Heatmap of busiest times of the day for each day of the week.
![Trips by Weekday](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_3.png)

4. Heatmap of busiest times, with different charts for each gender.
![Trips by Gender](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_4.png)

5. Heatmap shows the busiest days of the week, by gender.
![User Trips by Gender](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_5.png)

6. This map shows the locations of each bike station, larger circles indicate more rentals.
![Map of bike stations](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_6.png)

7. This chart shows the age of each user, with different colors for each gender.  There appears to be some irregularities with the data for birthdates for 1969.
![Users by age and type](https://github.com/AndyHerron/bikesharedata/blob/main/images/viz_7.png)

## Summary: Provide high-level summary, then provide suggestions for two additional visualizations that may provide more insight.
If you were using this data as the basis for starting up a bike sharing service in a different city, the "target market" would be males born after 1975. 
Most trips are less than 1 hour long, and peak usage will primarily be early mornings and early evenings - just before and after a typical workday.

### Suggested visualizations for further analysis
1. Some information that would be very helpful would be the percentage of bike trips that start and end at the same bike station.  How many logistical challenges will be faced moving bikes from less-utilized locations to preferred locations
so they are available during periods of high demand?

2. Do subscribers tend to make shorter or longer trips than occasional users?

=======
