# kickstarter-analysis
### Project Overview
The goal of this project is to analyze the results (success vs failure) of kickstarter campaigns in the "Theater" production category. The data set contains roughly 8 years of kickstarter campaign data. The primary factors (independent variables) that analyzed are "Launch Date", specifically the month of the year during which a campaign was launched (irrespective of year), and "Goals" which were financial targets to be met; these two variables were compared and analyzed with the target (dependent variable): whether the campaign resulted in a Success (met fundraising goal) or Failure (did not meet fundraising goal).

### Analysis and Challenges
In order to analyze the covariance / trends in data between launch dates, goals and kickstarter campaign outcomes, I created two separate sets of Pivots and Charts. 

The first PivotChart formed a table with data aggregated on Months; I utilized a line chart to examine the monthly trends over time and the campaign outcomes, which can be seen ![here](https://raw.githubusercontent.com/Dreski9000/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.png)

The second PivotChart examines the campaign results based on different goal brackets for the campaign financial targets ordered from least to greatest. The following chart illustrates the trend between campaign fundraising goals and their outcome ![Outcomes Based on Goals](https://raw.githubusercontent.com/Dreski9000/kickstarter-analysis/main/Outcomes_vs_Goals.png).

Some challenges are potential confounding variables that are outlined below, mainly not having access to campaign creator data.

### Analysis Results

The following can be concluded about the relationship / potential affect that a launch date (Month) may have on whether the campaign is successful or not:
  1. The number of successful campaigns appears to increase significantly from April to May, and peak in May, and begins to decline steadily until the end of the year. In short, summer seems to be the season that has a higher (on average) number of successful campaigns. 
  2. The number of failed campaigns appears to be relatively stable throughout the year, with some minor fluctuations; however, considering the total number of campaigns in each month, the implied ratio of successful campaigns is much higher in months of May - July.

The following can be concluded about the campaign outcomes based on financial goals / targets:
  1. Campaigns with targets below 10,000$ are more likely to succeed (>50% chance of success), with campaign with goals under $1,000 having the highest chance of success out of all brackets (>70%). All targets above $10,000 have a <50% chance of success; and campaigns with targets exceeding $45,000 have a low chance of success (<30%).

Based on our data points and analsis, the highest probability of successful "Theater" campaign would be launched in the month of May with a target below $1000.

Some of the potential limitations of this data set are outlined below:
  1. It would be helpful to have a mapping between campaigns and creators. Some creators might be reputable companies or individuals that already have had successful campaigns, which would ostensibly increase their probability of meeting their financial targets.
  2. Any metrics that could potentially be indicative of a campaign quality might correlate with the probability of a campaigns success, such as : number / variety of prizes, whether or not a campaign has a website, whether it has previous successful campaigns, whether or not it has a YouTube video, and even something like the size of the KickStarter webpage.

Some other potential avenues of exploration:
  1. Breakdown by subcategories vs outcomes
  2. Total length of campaign (window between created and closed) vs outcomes
  3. The length of the campaign name or / blurb vs outcomes
