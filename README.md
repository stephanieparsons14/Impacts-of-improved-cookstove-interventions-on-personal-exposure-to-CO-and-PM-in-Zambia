This Jupyter Notebook file is the software accompanying our submission to GeoHealth of "Impacts of improved cookstove interventions on personal exposure to carbon monoxide and particulate matter in Zambia."
Authors: Stephanie Parsons, Wesley Hayes, Gillian Kabwe, Francis Yamba, Nancy Serenje, Robert Bailis, Pamela Jagger, Andrew Grieshop

Abstract:

This notebook was built under notebook version 6.0.3 and Python version 3.7.6. It includes all analysis completed of raw CSV files and code for all figures and tables in the manuscript. Last updated August 6, 2024.
The notebook includes the follow analysis sections with a Table of Contents included for ease of use:
1. loading in various packages for analysis.
2. loading in CSVs containing CO and PM2.5 exposure hourly diurnal averages for baseline (2019) and endline (2021); figures comparing them.
3. loading in CSVs containing cook/ household information, 24-hour average CO and PM2.5 for baseline and endline; various figures comparing them.
4. loading in CSVs from 4 PurpleAir sensors; correcting and averaging raw PurpleAir data; comparing exposure and temperature measurements to PurpleAir data.
5. comparing baseline to endline exposure data.
6. applying multiple statistical modeling methods to analyze the impact of the two intervention stoves on cooks’ CO and PM2.5 exposures, including significance testing,
   difference-in-differences, and cross-secitional generalized least squares modeling.
7. loading in a CSV of household and primary cook characteristics during baseline for participant comparison.
8. loading in CSVs for filter corrections of real-time particle exposure sensors during endline.
9. repeating statistical modeling methods from #6 to include stove influenced (SI) hours and consider average SI CO and average SI PM2.5 as dependent variables in models.


Please contact stephanie.d.parsons@gmail.com with any questions.
