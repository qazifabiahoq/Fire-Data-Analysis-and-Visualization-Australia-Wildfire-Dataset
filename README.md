# Fire Data Analysis and Visualization: Australia Wildfire Dataset

## Project Description

This project analyzes wildfire activities across seven regions in Australia from 2005 onward. It focuses on understanding patterns in wildfire extent, intensity, and distribution over time and space, using key metrics such as fire area, brightness, radiative power, and confidence levels. The objective is to provide clear insights into wildfire dynamics to support better resource allocation and risk management.

## Who Will Benefit and Why

* **Government agencies** tasked with disaster response and wildfire management can use these insights to improve policy and resource deployment.
* **Environmental organizations** gain a deeper understanding of fire behavior across regions to inform prevention strategies.
* **Researchers** studying ecological and social impacts will find detailed temporal and spatial patterns useful.
* **General public and educators** can access comprehensible visualizations to increase awareness about wildfire trends in Australia.

## Data Source

The dataset comprises daily satellite observations related to presumed vegetation fires with high confidence (above 75%). It includes variables such as region, date, estimated fire area (km²), mean fire brightness (Kelvin), mean radiative power (MW), confidence statistics, and pixel counts, covering seven Australian regions: New South Wales, Queensland, South Australia, Tasmania, Victoria, Western Australia, and Northern Territory.

## Methodology

* Data was aggregated annually and monthly to analyze temporal changes in estimated fire area and brightness.
* Regional comparisons were performed using bar plots, pie charts, and histograms to reveal spatial variations in fire intensity and frequency.
* Correlation analysis between radiative power and confidence levels was conducted using scatter plots.
* Geographical visualization with Folium mapped the regions to provide spatial context.
* All visualizations aimed to reveal trends and highlight peak fire periods and affected regions.

## Key Findings

**What were the major changes in fire area over time?**

* The average estimated fire area peaked at 265 km² in 2012, with a notable increase between 2010 and 2012, matching Australia's known severe wildfire seasons.

**When did fire activity peak within years?**

* April 2011 and April 2012 recorded the highest monthly fire activity, coinciding with large-scale wildfire events.

**Which regions experienced the most intense fires?**

* New South Wales (NSW) and Northern Territory (NT) showed the highest average fire brightness, indicating more intense fires compared to other regions.

**How did the distribution of fire pixels vary by region?**

* Northern Territory accounted for 34.13% of vegetation fire pixels, closely followed by Western Australia at 32.37%. Tasmania and South Australia had minimal contributions (0.6% and 1.85%).

**What was the pattern of fire brightness values?**

* Fire brightness mostly clustered around 5000 Kelvin, with 320 occurrences in that range, showing consistency in fire intensity, though NSW and NT had more extreme brightness events.

**Is there a correlation between fire intensity and confidence in measurements?**

* No significant linear correlation was found between radiative power (fire intensity) and confidence levels, suggesting confidence scores do not reliably predict fire strength.

**How is the spatial distribution of wildfires across Australia?**

* The map visualization confirmed that NT and WA have the highest fire activity, aligning with their large pixel counts and brightness levels.

## Conclusion

This analysis highlights distinct temporal and regional wildfire patterns across Australia. The 2011–2012 period was marked by unusually high fire activity and intensity, particularly in Northern Territory and New South Wales. Variations in fire brightness and pixel counts demonstrate uneven wildfire impacts, emphasizing the need for region-specific management strategies. The lack of correlation between radiative power and confidence indicates that multiple factors affect wildfire characteristics beyond measurement certainty. Geospatial visualization supports targeted resource planning by clearly identifying hotspots. Overall, the findings aid stakeholders in anticipating wildfire risks and tailoring response efforts effectively.

## Recommendations

Focused wildfire management efforts should prioritize regions with consistently high fire intensity and area, especially NT and NSW. Incorporating temporal trends such as peak months can optimize resource allocation. Continued integration of satellite data with ground-based observations will improve prediction accuracy and confidence assessments. Enhanced public awareness campaigns informed by this data may increase preparedness in vulnerable areas.

## Authors

Dr. Pooja

Copyright © 2023 IBM Corporation. All rights reserved.

## Completed by

Qazi Fabia Hoq (Data Science Professional Certification, IBM)

## Acknowledgement

This project is part of the IBM Data Science Professional Certification on Coursera. The dataset and task guidelines were provided as course materials. The analysis was completed under the guidance of Dr. Pooja, contributing to practical learning and skill development.
