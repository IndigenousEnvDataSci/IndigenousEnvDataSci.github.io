# Year 1 Challenge Themes

## Aquatic Ecosystems

**WHAT:** Freshwater temperature and dissolved oxygen 

**WHERE:** 1 lake and 1 river NEON sites. Click to expand the image in a new tab.
![](images/Barco Posey Sites.png)

**WHEN:** Daily forecasts with a 7-day forecast horizon at the beginning of the month and submitted monthly from May 31-August 2021; later submissions after the May 31 start are permissible

**WHY:** Temperature and oxygen are critical for life in aquatic environments and can represent the health of the system

**WHO:** Open to any individual or team that registers

**HOW:** REGISTER your team and submit forecast

### Overview

In streams and rivers, forecasting water temperature can be meaningful for protecting aquatic communities while maintaining socio-economic benefits (Ouellet-Proulx et al. 2017). In lentic systems, successfully forecasting surface water temperatures can be important for fisheries and water utilities that need to manage the outflowing temperatures (Zhu et al. 2020). Recently, water temperature forecasts in lakes have been used to predict seasonal turnover when nutrients from the bottom can be mixed to the surface and impair the water quality. 

Dissolved oxygen concentration is a critically important variable in limnology. Forecasts of dissolved oxygen in freshwaters is the first step to understanding other freshwater ecosystem processes. For example, oxygen serves as the gatekeeper to other biogeochemical reactions that occur in rivers and lakes. Preemptive forecasts of dissolved oxygen concentrations can anticipate periods of high or low oxygen availability, thereby providing insight into how the ecosystem may change at relatively short timescales. 

### Challenge

This design challenge asks teams to produce forecasts of mean daily surface water temperature and/or dissolved oxygen in one NEON lake and/or one NEON river site in the Southeastern U.S. 35 days from the first of the month. The NEON lake site is Barco Lake (BARC) in Florida and the NEON river site is Posey Creek (POSE) in Virginia. Each forecast will start on the 1st day of each month and must forecast up to 7 days into the future. Forecasts are welcome to go past the 7 day timeline but those dates will not be evaluated. 

Teams are asked to submit their 7 day forecasts of NEON surface water temperature and/or dissolved oxygen measurements along with uncertainty estimates and metadata. Any NEON surface water temperature and/or dissolved oxygen data prior to the 7 days being forecasted will be provided and may be used to build and improve the forecast models. Other data (other than temperature and/or dissolved oxygen data provided from NEON) can be used so long as they are not from the 7 days being forecasted at the beginning of each month, that they are publicly available, and that teams provide access (minimum of URL, but ideally a script) to all teams in the challenge.

Submissions of forecast and metadata will be through https://data.ecoforecast.org/minio/submissions/ using prescribed file formats described in the challenge theme documentation (PENDING).

Forecasts will be scored and compared using the Continuous Ranked Probability Score, a metric that combines accuracy and uncertainty estimation (Gneiting, T., & Raftery, A. E., 2007). 

#### Data: Training and Evaluation
The R script for generating the evaluation and training data can be found at: https://github.com/eco4cast/neon4cast-aquatics

The challenge uses the following NEON data products:
DP1.20264.001: Temperature at specific depth in surface water
DP1.20288.001: Water quality

### Data: Targets

A file with previously released NEON data that has been processed into “targets” is provided below. The target script can be found here. The same processing will be applied to new data that are used for forecast evaluation. Before the Aquatics challenge begins, a processing script will be available in the neon4cast-aquatics GitHub repository.

### Detailed Protocol

Details of the targets, how they are calculated, descriptions of the target files, and examples of other environmental variables that could be used in the Challenge are HERE. 

Access Targets

Download an example of a forecast output format for submission HERE

### Timeline
The timeline is determined by the data latency provided by NEON. NEON data is released in month long sets, 2 weeks after the month ends. 

NEON data for a given month is scheduled to be released around the 15th of the following month. Once the NEON data for a previous month is released, teams have between the release of those data to the end of the month to forecast the 7 days of the current month (see table). 

Forecast submissions will due beginning May 31, 2021 at 11:59 Eastern Standard Time (UTC−05:00) for forecasts that start May 1. Final forecast submissions will be due on August 31, 2021 at 11:59 Eastern Standard Time (UTC−05:00) for forecasts that start August 1.

As an example, if NEON water temperature data is released on April 15 for data from March 1 - 31, teams then can use these new March data and the NOAA GEFS forecast issued on April 1 at 00:00 to help generate forecasts from April 1 - April 8 (7 days). This April forecast is due by 11:59 pm EST on April 30. The forecast issue date for the April forecast is April 1, so no new observational data from after that date can be used to constrain forecasts and the forecast should use the weather forecast issued at midnight April 1 (i.e. start of day) as the driver (not the observed meteorology in April or forecasts made at later dates).

Evaluation will occur as new NEON data is released.

![Forecast Timeline Table](images/Aquatics Forecast Timeline.png)

### Design Team
James Guinnip, Kansas State University  
Sarah Burnet, University of Idaho  
Ryan McClure, Virginia Tech  
Chris Brown, National Oceanic and Atmospheric Administration  
Cayelan Carey, Virginia Tech  
Whitney Woelmer, Virginia Tech   
Jake Zwart, United States Geological Survey  

### Partners

The challenge is hosted by the Ecological Forecasting Initiative (EFI; https://ecoforecast.org/) and its U.S. National Science Foundation sponsored Research Coordination Network (EFI-RCN; https://ecoforecast.org/rcn/).

Data used in the challenge are from the National Ecological Observatory Network (NEON): https://www.neonscience.org/. 

Scientists from NOAA and USGS have been involved in the design of the challenge.

### References

Gneiting, T., & Raftery, A. E. (2007). Strictly proper scoring rules, prediction, and estimation. Journal of the American Statistical Association, 102(477), 359–378. https://doi.org/10.1198/016214506000001437

Ouellet-Proulx, S., St-Hilaire, A., and Bouchar, M.-A.. 2017. Water temperature ensemble forecasts: Implementation using the CEQUEAU model on two contrasted river systems. Water 9(7):457. https://doi.org/10.3390/w9070457

Zhu, S., Ptak, M., Yaseen, Z.M., Dai, J. and Sivakumar, B. 2020. Forecasting surface water temperature in lakes: a comparison of approaches. Journal of Hydrology 585, 124809. https://doi.org/10.1016/j.jhydrol.2020.124809

## Terrestrial Carbon and Water Fluxes

## Tick Populations

## Phenology

## Beetle Communities
