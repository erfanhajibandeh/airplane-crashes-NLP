Project Title: Analysis of Historical Airplane Crash Data: Causes, Trends, and Implications

1. Introduction
Airplane crashes have been a major concern for the aviation industry since its inception. Despite significant advancements in aircraft technology and safety regulations, crashes continue to occur, resulting in the loss of many lives. In this project, I propose to conduct an exploratory data analysis of the comprehensive dataset on airplane crashes since 1908, to identify patterns and trends. Novel analysis was completed using machine learning algorithms, including Principal Component Analysis and K-Means to reveal better insights with some interesting visualizations. The methodology section explains the dataset, assumptions, and the data analysis. Finally, the questions that were presented in the proposal are answered in the conclusion section.

2. Methodology
2.1. Data Source

The Airplane Crashes Since 1908 dataset includes a full history of airplane crashes throughout the world, from 1908 to 2009. The dataset comprises 5268 observations with 13 features. Some missing values are described in Table 1. Additionally, a secondary dataset was used to estimate the total number of airplane departures annually, investigating the relationship between crash occurrences and total departures.

2.2. Explanatory Data Analysis

Text analysis of the Summary and Operator columns determined whether crashes were related to the military. This analysis categorized crashes as either military or non-military. The data revealed that out of 5240 crashes, 781 were military, and 4469 were non-military. Further analysis explored crash trends by month, day of the week, and hour of the day, providing insights into potential contributing factors.

2.3. Clustering

K-means clustering was applied to analyze the Summary of flight descriptions, categorizing crashes into clusters based on text content. Principal Component Analysis (PCA) was used to reduce dimensionality while retaining essential information. The combination of K-Means and PCA effectively categorized crashes into three clusters representing the main phases of flight: takeoff, flight, and landing.

3. Conclusion
The analysis revealed that the dataset included 5240 crashes, with 781 being military and 4469 non-military crashes. The report highlighted trends, such as increased accidents in December and August, higher accident rates on Thursdays and Fridays, and a peak in accidents between 7 AM and 6 PM. The decreasing ratio of fatalities to total passengers indicated improving aviation safety.

Additionally, the report identified Aeroflot as the operator responsible for the most crashes. K-means clustering and PCA successfully classified crashes into three clusters based on flight descriptions, showing distinct patterns related to takeoff, flight, and landing stages. This novel approach enhanced our understanding of crash categorization.