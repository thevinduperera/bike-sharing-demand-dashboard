# Bike Sharing Demand Dashboard

Interactive Excel dashboard analyzing how weather, season and day type affect bike-share demand.


## Business question
How do weather, season and day type affect demand?


## Key findings
- **Season matters a lot.** Average daily rides are highest in summer (5,644) and lowest in winter (2,604).
- **Most riders are commuters, not tourists.** Registered users make up 81% of all rides. Casual users are only 19%, but they ride much more on weekends (1,371/day) than weekdays (607/day). It's the opposite pattern from registered users who ride more on weekdays (3,978) than weekends (2,959).
- **Weather has a bigger impact than season.** Rides drop 63% on rainy/snowy days versus clear days (4,877 to 1,803 average daily rides). That's a steeper drop than the difference between the best and worst season, summer versus winter (a 54% drop, 5,644 to 2,604).
- **There's a comfort zone for temperature.** Ridership is highest between 15–25°C. It drops off at colder temperatures, but only mildly at hotter ones. People are more put off by cold than by heat.
- **Ridership grew a lot year over year.** Average daily rides went up 64% from 2011 to 2012.


## Tool
Built entirely in Excel - pivot tables, slicers, XLOOKUP-based categorical decoding.


## Data
UCI Bike Sharing Dataset
