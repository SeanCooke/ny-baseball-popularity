# New York Baseball Team Popularity
Between 1962 and 2018, there have been two Major League Baseball teams in New York, the Mets and the Yankees.  Each team's popularity has fluctuated over time.  We will create a visualization that attempts to answer the question 'Who has been New York's most popular baseball team between 1962 and 2018?'

## System Requirements
Built for [Anaconda 3](https://www.anaconda.com/distribution/) (Python 3.7.3, Pandas 0.24.2, NumPy 1.16.4, and Matplotlib 3.1.0)

## Data Visualization
We will use annual home-game attendance as a proxy for popularity.  We will consider a team 'more popular' if they had a higher annual home-game attendance.  Since most MLB games do not sell-out, we do not normalize by stadium size and assume stadium size is not a limiting factor in team popularity

We also find that normalizing by stadium size shows similar results and makes for a less intuitive visualization

![New York's most popular baseball team between 1962 and 2018](https://github.com/SeanCooke/ny-baseball-popularity/blob/master/ny-baseball-popularity.png?raw=true)

## Conclusion
Between 1962 and 2018, the New York Yankees have generally been the more popular baseball team in New York.  This is due, in large part, because the Yankees have won 8 World Series championships in this time while the Mets have won only 2

The only times the Mets have been more popular than the Yankees have been around their two World Series championships (1969 and 1986).  This shows that the most popular baseball team in New York is directly related to the probability that team will win the World Series

Another interesting trend shown in this visualization is the meteoric rise in popularity of both teams between the strike-shortened season in 1994 and the peak of the steroid era in the early 2000's with annual attendance more than doubling for both teams during that time period. This increase in popularity for the sport could explain Major League Baseball's initial reluctance to discipline players for steroid use though more research would need to be done to support this claim
