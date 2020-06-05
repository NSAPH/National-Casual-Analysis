Perparation of Data and Statisical Analysis
================
Ben Sabath
June 05, 2020

This directory contains code covering the creation of the data set used
for anaylsis by Xiao Wu in his paper “Evaluating the Impact of Long-term
Exposure to Fine Particulate Matter on Mortality Among the Elderly.”.

The directory `Confounders` contains the process by which the zip code
level demographic data, smoking and bmi data, and weather data are
aquired and prepared for use. `Exposures` describes the preperation of
the PM2.5 data. `HealthOutcomes` contains the code used to select data
from the Medicare Beneficiary Summary Files. Finally, `MergedData`
contains the process by which all these data sources are combined and
cleaned in order to be analyzed by the code in `StatisticalAnalysis`.

We have included as much data as we are allowed to share and can
feasibly include in a github repo (some files are too large to share).
Where we are unable to share data, we have provided instructions on how
to acquire the source data and prepare it for use with the data
pipelines.