# Aviation Safety Analysis
![](https://www.google.com/url?sa=i&url=https%3A%2F%2Ffinance.yahoo.com%2Fnews%2Ftop-16-aircraft-manufacturers-world-143842662.html&psig=AOvVaw1cPjslDGzQHAPPNvq0fs1K&ust=1718482218545000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKjHlaPz24YDFQAAAAAdAAAAABAE)
## Overview

This project explores aircraft data in order to offer suggestions for a company looking to learn more about aviation safety. Based on descriptive data, we have identified key findings regarding the safety of various aircraft.These insights can assist the business in establishing guidelines for their upcoming venture in the aviation sector.

-An [interactive dashboard](https://public.tableau.com/views/projectphaseone/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) is available to explore our data and conclusions. 

## Business understanding
This business is diversifying its holdings by venturing into new markets. In particular, they are eager to buy and run aircraft for both individual and commercial use, yet they have no knowledge of the possible hazards associated with aviation.It requires assistance in identifying which aircrafts have the least amount of danger when launching a new company aircraft.

### source of data
The[dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)utilized data sourced from Kaggle, specifically obtained from the National Transportation Safety Board. This dataset encompasses information spanning from 1962 to 2023, focusing on civil aviation accidents and chosen incidents occurring within the United States and international waters.

### Description of data
- I investigated the columns `Injury.Severity`, `Make,` and `Model` in order to understand which flight purposes are the riskiest, and which makes and models are the safest within commercial purposes.Also I needed Distribution of accidents and incidents over the years inorder to confirm the rise of accidents and incidents over the years.
- 
### risk-metrics 
I used various risk-metrics to come up with the best aircrafts
1. -Accident-Incident-occurences -Obtaining the least amount of risk As per the Accident and incident count
2. -Injuries -Checking to eliminate the models with high number of incident causing injuries
3.-Damage-Filtering to get the minor category which has the least damage.
4.-Amatuer-Built- Used this for getting only proffessional airplanes.
5.Engine-type- Get the engine type associated with less incidents

### Conclusion
I recommend Boeing-b737-2h4 and Rockwell-na-265-80 because they are associated with the least risks of accidents ,incidents,injuries and damages.
Also they are proffessional well built.
The engine type built on this aircraft have the least number of incidents associated with them.

   
   

- 
