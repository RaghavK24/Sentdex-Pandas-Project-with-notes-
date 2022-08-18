# US Presidential Election Correlation Project

In this project 4 datasets are used :

### Minimum Wage Data.csv :
This dataset goes from 1968 to 2017, giving the minimum wage (lowest amount of money that employers can pay workers by the hour), by state.

### output.csv :
This data represents the Local Area Unemployment Statistics from 1990-2016, broken down by state and month

### pres16results.csv :
This dataset includes county-level data from the 2016 US Presidential Election

### state_abbv0.csv :
This dataset contains postal code for each state. This would be used for making sure that the abbreviation for states is the same in county_15 and pres16 variables in our code

## Aim :

The purpose of this project is to look at election data by county and see if there's a relationship between voting, minimum wage, and unemployment. We would be comparing vote percentage for US Presidential Election nominee Donald Trump by county and the minimum wage and unemployment rate for the respective counties.

## Result :

It looks like there's a slightly positive relationship (correlation) between the unemployment rate and minimum wage, but also a pretty strong covariance, signaling to us that these two things do tend to vary together. It just looks like, while they definitely vary together, the actual impact of one on the other isn't very substantial

Curiously, min_wage appears to have a negative correlation with the pct vote for Trump, so as minimum wage rises, people are less likely to vote for Trump, for example. That makes sense since higher minimum wages are typically a Democratic agenda, though it is fairly curious that, while correlated, they do not attempt to vary together
