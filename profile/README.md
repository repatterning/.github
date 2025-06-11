[The Artificial Intelligence Unit](https://github.com/theartificialintelligenceunit)

<br>

### About

This hub host's the repositories of the <a href="https://theartificialintelligenceunit.github.io/intelligence/html/in-river-predictions.html">river levels intellligence pages</a>.  

<br>

### Repositories

&nbsp; | purpose
:--- | :---
<a href="https://github.com/repatterning/daily" target="_blank">daily</a> | Retrieves the latest river level measures, vis-à-vis the previous 24 hours.
<a href="https://github.com/repatterning/structures" target="_blank">structures</a> | Structures the latest data, deals with anomalies, e.g., missing measure points.
<a href="https://github.com/repatterning/measures" target="_blank">measures</a> | Prepares raw measures for graphing.
<a href="https://github.com/repatterning/contrasts" target="_blank">contrasts</a> | Calculates hourly percentage changes, and prepares the calculations for graphing.
<a href="https://github.com/repatterning/quantiles" target="_blank">quantiles</a> | Calculates quantiles and extrema, and prepares the calculations for graphing.
<a href="https://github.com/repatterning/drift" target="_blank">drift</a> | Calculates drift.
<a href="https://github.com/repatterning/variational" target="_blank">variational</a> | For Bayesian state space modelling of time series; <a href="https://github.com/repatterning/viability" target="_blank">viability</a> is its  corresponding evaluation repository.
&nbsp; | &nbsp;
<a href="https://github.com/repatterning/iac" target="_blank">iac</a> | Limited infrastructure as code notes; intentionally opaque.
&nbsp; | &nbsp;
<a href="https://github.com/repatterning/restart" target="_blank">restart</a> | For re-acquiring historic river level data


<br>

### Model & Data

<br>

**Model**

&nbsp; | description
:--- | :---
task | River level prediction
algorithm | Bayesian Structural Time Series + Variational Inference; Bayesian Inference & State Space Models
input | Hourly river level data
output | Future predictions; [t](https://github.com/repatterning/configurations/blob/3e4479768e18b86c806123f37d5394d4f0489e1b/src/artefacts/architecture/variational/arguments.json#L10) hours ahead.
prediction<br>schedule | Mondays & Fridays

<br>

**Data**

&nbsp; | description
:--- | :---
name | River Level Data
modality | Time Series
raw data source | [SEPA API](https://timeseriesdoc.sepa.org.uk) (Scottish Environment Protection Agency Application Programming Interface)

<br>
<br>

<br>
<br>

<br>
<br>

<br>
<br>
