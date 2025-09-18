
<br>

### Repositories

&nbsp; | purpose
:--- | :---
<a href="https://github.com/antecedents/raw" target="_blank">raw</a> | Retrieves the accident & emergency data.
<a href="https://github.com/antecedents/measures" target="_blank">measures</a> | Prepares raw measures for graphing.
<a href="https://github.com/antecedents/decompositions" target="_blank">decompositions</a> | Determines plausible trend, season, and residue components per hospital/institution series.
<a href="https://github.com/antecedents/quantiles" target="_blank">quantiles</a> | Calculates quantiles and extrema, and prepares the calculations for graphing.
<a href="https://github.com/antecedents/variational" target="_blank">variational</a> | For Bayesian state space modelling of time series; <a href="https://github.com/antecedents/viability" target="_blank">viability</a> is its  corresponding evaluation repository.
&nbsp; | &nbsp;
<a href="https://github.com/antecedents/iac" target="_blank">iac</a> | Limited infrastructure as code notes; intentionally opaque.
&nbsp; | &nbsp;
<a href="https://github.com/antecedents/references" target="_blank">references</a> | For retrieving reference data, e.g., health board data, etc.

<br>

### Model & Data

<br>

**Model**

&nbsp; | description
:--- | :---
task | Accident & Emergency Attendance Prediction
algorithm | Bayesian Structural Time Series (STS) + Variational Inference
input | The accident & emergency attendance time series of the previous weeks.
output | The training phase forecasts, the testing phase predictions, and future predictions (9 weeks ahead)
operations<br>schedules | The raw data is updated weekly, and sometimes data numbers are corrected, hence <ul><li><b>Predictions</b>: Weekly, Tuesdays, 9 Weeks Ahead</li><li><b>Model Re-training</b>: Weekly, Tuesdays, Before Predictions</li></ul>

<br>

**Data**

&nbsp; | description
:--- | :---
name | Weekly Accident & Emergency (A&E) Activity, and Waiting Times
modality | Time Series
brief description | Every week, on a Tuesday, <a href="https://www.publichealthscotland.scot/" target="_blank">Public Health Scotland</a> releases an updated CSV file consisting of (a) counts of weekly A&E attendance at approximately 30 hospitals, and (b) waiting time metrics.  The weekly counts span Monday → Sunday. <ul><li><a href="https://www.opendata.nhs.scot/dataset/weekly-accident-and-emergency-activity-and-waiting-times" target="_blank">Detailed data description.</a></li><li><a href="https://www.opendata.nhs.scot/" target="_blank">Scottish Health and Social Care Open Data</a></li></ul>
raw data access | <a href="https://www.opendata.nhs.scot/dataset/weekly-accident-and-emergency-activity-and-waiting-times/resource/a5f7ca94-c810-41b5-a7c9-25c18d43e5a4" target="_blank">Weekly Accident & Emergency Activity, and Waiting Times</a>

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>
