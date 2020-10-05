# Kickstarting with Excel

## Overview of Project

### The purpose of the analysis is to identify trends in existing kickstarter data to help the client Louise's play, Fever, achieve its fundraising goal. I focused the analysis on two areas: the correlation between campaign outcomes and campaign launch date, and the correlation between campaign outcomes and campaign funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The collected "Outcomes Based on Launch Date" data tells us that the number of launched theater related Kickstarter campaigns peaks in May. June and July are the 2nd and 3rd most popular months to launch campaigns respectively. Within these three months we also see the greatest success rate among launched campaigns.

### Analysis of Outcomes Based on Goals

The collected "Outcomes Based on Goals" data offers a less clear visual picture. The data at first seems to relay a steady decline in the rate of successfully funded campaigns as the funding goal increases. However this trend is upset by the data entries in the $35,000-$44,999 where successful campaigns outnumber the failed campaigns. Though it should be noted that a majority of the data points fall between the <$10000 range. 

### Challenges and Difficulties Encountered

The biggest challenge I encountered, and one I failed to find an elegant solution to, was refreshing pivot table data.  A few times throughout the analysis I would create a pivot table only to realize that there was an error in the data or with one of my formulas the table was pulling from. After I'd fixed the issue with a formula, the pivot table didn't update itself to feature the new data. What seemed like the obvious answer, the "Refresh" button under the "Pivotchart Analyze" tab, would eliminate whole sections of my table. I'm not exactly sure why this was the case. It may be an error on my part. My workaround was to check the "Refresh data when opening file" box in the "Pivot Table Options" window. 

Then when I needed to refresh the data in the pivot table, I would close and reopen the file. Like I said: inelegant.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. With a healthy number of data entries spread throughout the year, I feel comfortable recommending a campaign launch in May/the beginning of summer. 
2. This analysis could benefit from greater specificity. Instead of just looking at launch month data from "Theater" campaigns, we could just look at the sub-category "plays" data set. As it exists this data may not be the most relevant to what would work for Louise's play.

- What can you conclude about the Outcomes based on Goals?

1. We chose the wrong approach to this data set. With a majority of the data points (nearly 90%) living between our first three dollar amount ranges, our the information in table and graph becomes less valuable as it continues. With fewer data points to work with, the percentages begin to vary wildly. This is why the back 3/4ths of our line graph displays no understandable patterns.
2. It's possible with a more focused look at the campaigns launched with funding goals <$10000 we would be able to identify a trend that supports a correlation between lower funding goals and successfully funded campaigns. That's what the data seems to indicate at the beginning of our table.

- What are some limitations of this dataset?



- What are some other possible tables and/or graphs that we could create?

With a quick view of the "staff pick" and "spotlight" columns, filtered to display "true" values, there appear to be many successfully funded campaigns. i'd love to eamin how much of a positive influence attention from kickstarter etitorial and marketing can have on a campaign. And from there I would like to see what sorts of campaigns are more likely to recieve spotlighting/staff pick. It may be that few plays are granted additional exposure because they are smaller/local affairs. 
