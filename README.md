# Census Bureau Net Domestic Migration Analysis

## Overview

### Purpose
Analyzed the Net Domestic Migration numbers from April 1, 2020 to July 1, 2022 (essentially since COVID-19 lockdown mandates). A state's `political lean` was also analyzed to see if it could be a potential influence of net domestic migration.

### Resources
- Data: 
    - [US Census Bureau Data (csv)](Data/US_Census_Bureau/cumulative_net_domestic_migration_20200401-20220701.csv)
    -  [2022 Partisan Lean Scores (txt)](Data/fivethirtyeight_data/partisan_lean_STATES_2022.txt) | [FiveThirtyEight Partisan Lean Scores (website)](https://fivethirtyeight.com/features/how-red-or-blue-is-your-state-your-congressional-district/)
    
- Software: Python, pandas, Tableau Public 
- [Link to Tableau Public dashboard](https://public.tableau.com/app/profile/lee.terrell/viz/USA-CumulativeDomesticNetMigrationApril12020-July12022/USACumulativeDomesticNetMigration)

## Observations

### Mapping Migration
<img src='Images/Domestic Net Migration 20200401 - 20220701.png'>
This map depicts the Cumulative Domestic Net Migration from April 1, 2020 to July 1, 2022 as red (net negative migration) and green (net positive migration) arrows. The size of the arrow represents the net volume.
From this map we could hypothesize that Americans from the northeastern states are migrating to the more Republican leaning southeastern states. It would also appear that west coast Americans are migrating out of Democratic leaning states.

### From Blue to Red
<img src='Images/Bar Graph- Domestic Net Migration.png'>
Not only do we see that the greatest negative net migartion occurs in Democratic-leaning California & New York and the largest positive net migration is seen in Republican-leaning Florida & Texas, but we also see that the 12 states with the largest net migration volumes fall along party lines.

## Summary

### Conclusion
We do not know their political affiliation or other demographic data, but we can clearly see that Americans are migrating out of Democratic-leaning states and into Republic-leaning states.

### Next Steps
1. It would be interesting to see if a governor's political party had a stronger correlation to which states had positive or negative net migration (hypothesizing that a Dem governor might have stricter lockdown rules).

2. The Supreme Court overturned Roe v Wade on June 24, 2022. It will be interesting to see if that event had a measurable influence in the next release of Net Domestic Migration estimates (July 1, 2022 to July 1, 2023)