This Jupyter Notebook file is the software accompanying our submission to GeoHealth of "Impacts of improved cookstove interventions on personal exposure to carbon monoxide and particulate matter in Zambia."
Authors: Stephanie Parsons, Wesley Hayes, Gillian Kabwe, Francis Yamba, Nancy Serenje, Robert Bailis, Pamela Jagger, Andrew Grieshop

Abstract:
In 2019, ~7 million deaths globally were attributed to ambient and household air pollution (HAP) exposure. Eighty-four percent of sub-Saharan African households rely on polluting fuels (e.g., wood, charcoal) for cooking, leading to high levels of HAP. While switching to cleaner energy sources/fuels could decrease HAP levels, these fuels are not always available or affordable. Improved biomass cookstoves could provide an intermediate step supporting transitions from traditional biomass to clean burning fuels/stoves. We conducted two stove intervention trials in Lusaka, Zambia using targeted marketing and incentives to motivate traditional biomass stove users to switch to improved biomass stoves, either the Mimi Moto (pellet) or the EcoZoom (charcoal). We measured 24-hour CO (n=747) and PM2.5 (n=90) exposures of primary cooks. We implemented statistical approaches to estimate the effect interventions had on exposure: household-specific endline minus baseline exposure, ranksum testing, difference-in-differences analysis, and cross-sectional analysis. We found no evidence that switching from traditional charcoal stoves to either intervention stove resulted in statistically significantly lower exposures. However, electric stove use significantly reduced CO exposure, with greater displacement of traditional charcoal with electric cooking corresponding to greater exposure reductions. We found that changes in exposure were dominated by seasonal, regional, and neighborhood differences rather than individual household stove/fuel choices. A narrow focus on HAP exposure from cooking in urban settings is unlikely to yield expected exposure reductions. Policy makers should consider pollution reduction policies and interventions that target ambient air quality in tandem with strategies for mitigating HAP to address air pollution health burden.

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


Please contact stephanie.d.parsons@gmail.com with any questions.
