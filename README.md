# Fire Data Analysis and Visualization: Australia Wildfire Dataset
## Overview of the Dataset
The dataset focuses on wildfire activities across seven regions in Australia, spanning from 2005 onward. It encompasses various aspects of wildfire data, such as the fire area, brightness, radiative power, confidence levels, and pixel count, all related to presumed vegetation fires with a confidence greater than 75%. The key variables include:

Region: One of the seven regions in Australia (New South Wales, Queensland, South Australia, Tasmania, Victoria, Western Australia, Northern Territory).
Date: Timestamp in UTC, providing daily data.
Estimated_fire_area: The sum of the estimated fire area in km², focusing on presumed vegetation fires.
Mean_estimated_fire_brightness: The average brightness, measured in Kelvin, associated with flagged fire pixels.
Mean_estimated_fire_radiative_power: The daily mean radiative power in megawatts, indicating the intensity of the fire.
Mean_confidence: The daily average confidence level of the fire estimation.
Std_confidence: The standard deviation of the confidence level, indicating the variation in the estimates.
Var_confidence: The variance of the confidence level, measuring the spread in the confidence values.
Count: The number of fire pixels flagged for presumed vegetation fires.
Replaced: An indicator showing whether the data has been replaced with more accurate, high-quality data (e.g., after 2-3 months).
##  Part 1: Fire Area and Brightness Analysis in Australia
Key Tasks and Findings:
### TASK 1.1: Average Estimated Fire Area Over Time

Objective: To observe the changes in the average estimated fire area annually.
Method: Data was grouped by year, and the average estimated fire area was calculated.
Key Findings: There was a significant increase in fire area between 2010 and 2012, with a peak of 265 km² in 2012. This corresponds with Australia’s peak wildfire period during 2011-2012, highlighting the intensity of wildfires in that period.
### TASK 1.2: Average Estimated Fire Area by Year and Month

Objective: To explore the variations in the estimated fire area on a monthly basis.
Method: Data was grouped by both year and month to analyze monthly fire area.
Key Findings: The highest fire activity was recorded in April 2011 and April 2012, aligning with historical data on large-scale fires during these months.
### TASK 1.3: Distribution of Mean Estimated Fire Brightness Across Regions

Objective: To visualize how fire brightness varies across regions in Australia.
Method: A bar plot was created to compare the mean brightness across regions.
Key Findings: The regions of NSW (New South Wales) and NT (Northern Territory) exhibited the highest average fire brightness, indicating more intense fires in these areas. Queensland and Western Australia followed with slightly lower fire brightness.
### TASK 1.4: Proportion of Pixel Count for Presumed Vegetation Fires by Region

Objective: To visualize how the count of presumed vegetation fires varies across regions.
Method: A pie chart was created to display the proportion of presumed vegetation fires.
Key Findings: Northern Territory (NT) had the highest proportion of vegetation fire pixels (34.13%), followed by Western Australia (WA) at 32.37%. Tasmania (TA) and South Australia (SA) had much smaller proportions of presumed vegetation fires (0.6% and 1.85%, respectively).
### TASK 1.5: Histogram of Mean Estimated Fire Brightness

Objective: To understand the distribution of fire brightness values.
Method: A histogram was generated to visualize the frequency distribution of fire brightness.
Key Findings: Most fire brightness values clustered around 5000 Kelvin, with 320 occurrences in a specific bin. This indicates consistent fire brightness across most regions, although there were some spikes during certain periods.
### TASK 1.6: Distribution of Estimated Fire Brightness Across Regions

Objective: To compare fire brightness distribution across regions.
Method: A stacked histogram was created, differentiating regions by hue.
Key Findings: NSW had the most instances of high brightness values, followed by NT and Queensland. The other regions, like South Australia, Tasmania, and Western Australia, had fewer occurrences of extreme fire brightness, possibly indicating less intense fires in these areas.
### TASK 1.7: Correlation Between Mean Estimated Fire Radiative Power and Mean Confidence

Objective: To explore any correlation between radiative power and confidence levels.
Method: A scatter plot was used to observe the relationship between radiative power and confidence.
Key Findings: There was no significant linear correlation between radiative power and confidence levels. This suggests that confidence level does not consistently predict the radiative power of fires, despite radiative power being a strong indicator of fire intensity.
### TASK 1.8: Visualization of Regions on the Map of Australia Using Folium

Objective: To mark the seven regions on a map of Australia for geographical context.
Method: Folium was used to create an interactive map marking the regions with red circle markers.
Key Findings: This map visually presents the spatial distribution of wildfires across Australia, providing a geographic understanding of where the fire data is sourced from.



## Conclusion:

This analysis of wildfire data across Australia’s seven regions offers critical insights into wildfire dynamics, highlighting trends and regional disparities from 2005 onward.

Key temporal patterns were evident, with the average estimated fire area peaking at 265 km² in 2012, a stark increase compared to prior years. Significant fire activity was observed in April 2011 and April 2012, corresponding to Australia’s well-documented wildfire seasons. These periods underscore the need for focused mitigation strategies during peak fire months.

Regional analysis revealed that Northern Territory (NT) accounted for 34.13% of all presumed vegetation fire pixels, followed closely by Western Australia (WA) with 32.37%. In contrast, Tasmania (TA) and South Australia (SA) contributed only 0.6% and 1.85%, respectively, reflecting considerable variation in wildfire distribution. NSW (New South Wales) and NT exhibited the highest average fire brightness, with NSW consistently recording extreme values in the histogram analysis. This points to heightened fire intensity in these regions compared to others.

The distribution of fire brightness showed that most values clustered around 5000 Kelvin, with 320 occurrences in this range, suggesting a level of consistency in fire intensity across regions. However, extreme brightness values observed in NSW and NT highlight specific incidents of intense wildfires.

Interestingly, the scatter plot analysis revealed no significant linear correlation between radiative power (indicating fire intensity) and confidence levels. This indicates that confidence levels do not reliably predict the radiative power of fires, emphasizing the complexity of factors influencing wildfire characteristics.

The geographical visualization using Folium provided a spatial understanding of fire activity, marking all seven regions and their contributions. The regions with the highest fire activity—NT and WA—stand out geographically, aligning with their high pixel counts and brightness levels.

Overall, this analysis highlights the disproportionate impact of wildfires in specific regions, emphasizing the need for targeted strategies in Northern Territory and Western Australia. It also underscores the importance of temporal patterns, such as peak months and years, to anticipate and mitigate fire risks effectively. By understanding these dynamics, policymakers and environmental managers can allocate resources more efficiently and develop region-specific wildfire management plans. By integrating detailed historical data with and vizualizations, it becomes easier to explore and analyze wildfire data, helping decision-makers and researchers gain better insights into trends, hotspots, and patterns over time. This is beneficial for:

-Government agencies in disaster response and policy-making.
-Environmental organizations aiming to understand fire patterns and improve prevention strategies.
-Researchers studying the ecological and social impacts of wildfires.
-The general public, who can explore fire data trends in an accessible manner.

## Authors
Dr. Pooja

Copyright © 2023 IBM Corporation. All rights reserved.
## Completed by
Qazi Fabia Hoq (as part of the Data Science Professional Certification by IBM)

## Acknowledgement
This analysis is part of the IBM Data Science Professional Certification course on Coursera. The dataset used in this project was provided as part of the course, and the tasks were designed to help me apply data science techniques on real-world data. The guidance for this project was authored by Dr. Pooja, and I am grateful for the opportunity to enhance my skills through this comprehensive learning experience.







