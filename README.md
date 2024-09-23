# Data-Visualization
Tumor Volume Data Analysis
Overview
This project analyzes tumor volume measurements from a dataset involving mice treated with various drug regimens. The goal is to evaluate the effectiveness of these treatments in controlling tumor growth, assess variability in responses, and explore the influence of biological factors like weight and gender.

Dataset Description
The dataset contains the following key columns:

Mouse ID: Unique identifier for each mouse.
Timepoint: Measurement time of tumor volume.
Tumor Volume (mm³): Volume of tumors measured in cubic millimeters.
Metastatic Sites: Number of metastatic sites present.
Drug Regimen: Treatment assigned to each mouse.
Sex: Gender of the mouse.
Age (months): Age of the mouse in months.
Weight (g): Weight of the mouse in grams.
Additional summary statistics provide insights into the mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volumes across different drug regimens.

Analysis Summary
Key Findings
Effectiveness of Treatments: "Capomulin" and "Ramicane" are identified as the most effective treatments, demonstrating lower mean tumor volumes. Conversely, "Ketapril" and "Placebo" show higher mean values, indicating reduced efficacy.
Variability Assessment: Higher standard deviations in certain treatments suggest inconsistency in responses among mice.
Statistical Significance: Further statistical tests, such as ANOVA, are recommended to confirm observed differences in treatment efficacy.
Visualizations
The analysis includes various visualizations:

Bar Plots: Compare mean and median tumor volumes across drug regimens.
Box Plots: (If raw data is available) Illustrate the distribution and variability of tumor volumes.
Pie Charts: Display the gender distribution of unique mice.
Scatter Plots: Assess the relationship between mouse weight and tumor volume.
Future Directions
Conduct further statistical analyses to establish the significance of findings.
Investigate outliers and unusual responses, particularly in the "Infubinol" treatment group.
Explore potential adjustments in experimental design to ensure balanced representation of genders and drug regimens.
