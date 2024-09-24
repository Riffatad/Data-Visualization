# Pymaceuticals SCC Treatment:
  # Overview
This project analyzes data from a study conducted by Pymaceuticals, Inc. on the efficacy of various drug regimens for treating squamous cell carcinoma (SCC) in mice. The primary focus is on comparing the performance of the drug Capomulin against other treatments over a period of 45 days.
## Features
•	Data cleaning and preprocessing to handle duplicates.
•	Summary statistics for tumor volume across treatment regimens.
•	Visualization of treatment effects using bar plots and pie charts.
•	Analysis of correlation between mouse weight and tumor volume.
•	Linear regression analysis to model the relationship between weight and tumor volume.
Technologies Used
•	Python: Version 3.x
•	Pandas: Version 1.x
•	NumPy: Version 1.x
•	Matplotlib: Version 3.x
•	SciPy: Version 1.x
## Data
The dataset consists of two main files:
1.	Mouse Metadata: Contains information about each mouse, including ID and gender.
2.	Study Results: Contains tumor volume measurements for each mouse at various time points.
Data is combined into a single Data Frame for analysis.
Getting Started
## Analysis Steps
1.	Data Import and Preview:
o	Load the mouse metadata and study results data.
o	Combine them into a single Data Frame.
2.	Duplicate Handling:
o	Identify and remove duplicate entries based on Mouse ID and Timepoint.
3.	Summary Statistics:
o	Calculate mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volumes across different drug regimens.
4.	Visualization:
o	Create bar plots to visualize the total number of observations for each drug regimen.
o	Generate a pie chart showing the distribution of unique mice by gender.
5.	Final Tumor Volume Calculation:
o	Analyze the final tumor volumes for mice treated with Capomulin, Ramicane, Infubinol, and Ceftamin.
6.	Correlation Analysis:
o	Calculate the correlation between mouse weight and tumor volume.
o	Perform linear regression analysis.
7.	Scatter Plot with Regression Line:
o	Visualize the relationship between mouse weight and average tumor volume.
## Results
•	The analysis provides insights into the effectiveness of Capomulin compared to other treatment regimens.
•	Visualizations highlight the distribution of gender among mice and the number of observations per treatment.
•	Correlation results indicate the strength of the relationship between mouse weight and tumor volume.
## Conclusion
This project demonstrates the application of data analysis techniques to assess the efficacy of cancer treatments in a preclinical setting. The findings will support further research and development of effective anti-cancer medications at Pymaceuticals, Inc.

