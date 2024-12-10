
# Mortal Metrics

We created a combined dataset using the "NCHS - Leading Causes of Death: United States" and "Behavioral Risk Factor Data: Tobacco Use (2011 to present)" datasets which are publicly available from the CDC.

Our project aims to provide a concise and structured resource to analyze the relationship between mortality rates and tobacco use in the United States. This data can serve as a valuable tool for researchers and public health officials to identify trends and correlations that may exist between tobacco consumption patterns and specific causes of death.

By uncovering these trends, policymakers and community leaders can be empowered to take action. For example, if certain regions exhibit high rates of tobacco use (either specific types or overall) alongside increased incidences of particular causes of death, further investigation can be conducted to determine potential correlations.

If a causal relationship is identified, this information could be instrumental in designing targeted health campaigns, community education programs, or even legislation to regulate harmful tobacco products. Ultimately, this dataset aims to support evidence-based decisions that improve public health outcomes.


## Authors

- [@kyliehall27](https://github.com/kyliehall27)
- [@rmherman](https://github.com/rmherman)
- [@jordanrae3](https://github.com/jordanrae3)
- [@wlgagli26](https://github.com/wlgagli26)

## Documentation

[Documentation](https://github.com/rmherman/Team-Healthcare-Project/blob/14ea984bc2c87601f6e1cbda43842ab20248fbf8/Team_Healthcare_Project.ipynb)


## Lessons Learned

#### Different Time Periods
We found that the Leading Causes of Death dataset spans from 1999 to 2017, while the Tobacco Data starts in 2011 and continues to the present. The mismatch in time ranges limited our ability to fully compare trends across all years.

To overcome this, we limited our dataset to only the overlapping years (2011–2017). Unfortunately this does discard valuable historical trends from the mortality dataset prior to 2011 and smoking data after 2017.

#### Differing Data Formats
The datasets had different column headings and structures, leading to confusion when attempting to merge or analyze them together.
We renamed the column headings from the mortality dataset to make it explicit they were related to mortality. We standardized variable names and ensured consistency in formatting for easier integration and interpretation. In addition, we converted the mortality dataset values to percentages to match the smoking dataset.

#### Geographical and Demographic Inconsistencies
The datasets had differences in geographic coverage. The mortality dataset included U.S. territories while the tobacco dataset focused only on states within the U.S. To account for this, only areas present in both datasets were utilized, leading to a potential loss of additional insights for territories or specific regions.
## Licenses

NCHS - Leading Causes of Death: United States:
[Public Domain U.S. Government](https://www.usa.gov/government-copyright)

Behavioral Risk Factor Data: Tobacco Use (2011 to present): [Open Data Commons Attribution License](https://opendatacommons.org/licenses/by/1-0/)
## Screenshots of Potential Application

![Heatmaps](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

![Correlation using r-value](https://via.placeholder.com/468x300?text=App+Screenshot+Here)