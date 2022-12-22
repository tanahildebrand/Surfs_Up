# Surfs Up Challenge
## Overview
An investor is considering opening a surf shop in Oahu, Hawaii. They are interested in learning about weather trends in June and December to determine if the shop would be viable all year long. They provided historical weather data for Oahu in the form of a SQLite database.

## Results
 - As June is the summer month we are analyzing, we are focused on making sure the temperatures do not get too high. High temperatures could prevent surfers from coming to Oahu and purchasing from the surf shop. The max temperature in June is 85 degrees with an average of 75 degrees, which is a favorable temperature for being outside in water.
      ### June Temperature Statistics
      ![June Temp Summary](/Module_Challenge/Resources/June_Temp_Stats.png)
 - As December is the winter month we are analyzing, we are focused on making sure the temperatures do not get too low. Low temperatures could prevent surfers from coming to Oahu and purchasing from the surf shop. The min temperature in December is 56 degrees with an average of 71 degrees, which is a favorable temperature for being outside in water.
      ### December Temperature Statistics
      ![Dec Temp Summary](/Module_Challenge/Resources/December_Temp_Stats.png)
- The range of temperates in June (64-85 degrees) and December (56-83 degrees) show an overlap of temperatures in the range of 64-83 degrees. In addition, the average temperatures in June (75 degrees) and December (71 degrees) are only 4 degrees apart. Assuming temperature is the lone determination of whether the shop will succeed, I would agree. The temperatures are conistently welcoming.

## Summary
In addition to temperature, other weather data should be considered when trying to determine if seasonal fluxuations would affect sales at the surf shop. I completed two addition queries based on the precipitation.
 - The max precicipitation in June (4.43 inches) and December (6.42 inches) shows that the winter has an increase in precipitation of about 45%.
 - The average precicipitation in June (0.14 inches) and December (0.22 inches) shows that the winter has an increase in precipitation of about 57%.
 
 Based on the above, the precipitation by season varies far more than the temperature by season. This variability could affect the desire to surf in Oahu in December, and thus risk sales. I suggest further analysis of consumer habits be researched before removing precipitation as a risk factor.

### June Precipitation Statistics
![Jun Precip Summary](/Module_Challenge/Resources/June_Precip_Stats.png)

### December Precipitation Statistics
![Dec Precip Summary](/Module_Challenge/Resources/December_Precip_Stats.png)
