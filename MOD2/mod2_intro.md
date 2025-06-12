(mod2)=
# [Module 2: Exploring water quality for bull trout reintroduction](https://github.com/IndigenousEnvDataSci/EJ-DS/tree/main/Mod2_water)

Water is a valuable resource that is important for maintaining many aspects of a community’s well being. “Water quality” captures many components of the chemistry, biology, and physics of fresh water. In this module, we will study data about two of these components, water temperature (T) and dissolved oxygen (DO).

Bull trout are a culturally important, but threatened species of fish native to the U.S. Northwest and the Canadian Rockies. They provide an example of how water quality affects community culture, because, to thrive, bull trout require water temperatures below 14 $^\circ$C and dissolved oxygen levels above 6.5 mg/L. Such cold clean water conditions are growing scarcer due to climate warming and pollution.

It is also important to note that water temperature and levels of dissolved oxygen are related. As water temperature increases, dissolved oxygen levels decrease in water. This is concerning as climate warming has the power to increase water temperature, causing dissolved oxygen to dip to unhealthy levels for aquatic life.

In this module, we will use data about water quality trends to help K’avi Fish and Wildlife managers decide which of two streams would be best for a reintroduction of bull trout on tribal land. The tribe only has funding to bring the bull trout back to one stream. They have narrowed the choice of possible locations for the reintroduction to two streams, where temperature and D.O. have been monitored for about 15 years. Neither site is perfect, but they are both pretty good options. Your job is to analyze the temperature and D.O. data to help the tribe decide which is the best site.

The upstream source of Stream A is a groundwater spring. Water in this stream is very clean and temperatures are steady because groundwater temperatures tend to match average yearly temperature. The upstream source of Stream B is an alpine lake that is fed by a glacier. The glacial melt-water is very cold and clean, but the glacier is shrinking as climate warms, so the cold-water input to the lake is growing smaller over time.

## Data science topics covered:

-   Loading and previewing data from CSV files
-   tidy data, including new commands `pivot_longer()` and `full_join()`
-   handling NA data 
-   grouping and summarizing data with `dplyr`
-   data visualization with `ggplot` : scatter plots and time series, grouping by color 

## Module goals:

1. Explore water quality data of temperature and dissolved oxygen using methods learned in Module 1.

2. Compare water quality across two different sites using statistics and data visualization 

3. Consider how water quality data can help communities make decisions to protect culturally important species. Use all the analyses conducted (summary statistics, scatter plots, and time series plots) to make recommendations to the K’avi fisheries managers about which stream is a better bet for supporting healthy bull trout populations on tribal land. How does each analysis help you understand patterns in water quality? Which analysis was most useful?


## Learning goals: 

1.  Students will review skills learned in Module 1, including loading and previewing data, descriptive statistics, and making scatter plots.

2.  Students will learn to wrangle data into a “tidy” format that makes analysis and plotting easier.

3.  Students will practice how to “debug” code, in other words, we’ll learn how to fix common problems that we see when using real world data.

4.  Students will create graphs of data over time. These are called “time series” graphs.


## Note for instructors: 

From the scientific analysis perspective, this module highlights why it is useful to visualizing data in multiple ways. There is one question: “Which of two streams has water quality most appropriate to maintain a healthy bull trout population?” But we ask it three times, after seeing summary statistics, then a scatter plot, then time series plots. The summary statistics and the scatter plot show that Stream B generally has better water quality than Stream A, but the time-series graph shows that both temperature and dissolved oxygen are getting worse for bull trout. The question of which stream is a better choice (the one with better values or the one without a dangerous trend) is for the class to discuss.

**Sources on bull trout habitat:** 

Letourneau, M., Lesch, H., & Owen, J. (2022). Freshwater Temperature and Dissolved Oxygen Tolerance of Coldwater Fish Species in the Pacific Northwest in Freshwaters. https://gaftp.epa.gov/Region10/ID-Temperature/Bundled-BE-Final/Attachment%207%20Salmonid%20Litrev.pdf

Maret, T. R., & Schultz, J. E. (2013). Bull trout (Salvelinus confluentus) movement in relation to water temperature, season, and habitat features in Arrowrock Reservoir, Idaho, 2012 (Report Nos. 2013–5158; Scientific Investigations Report, p. 36). USGS Publications Warehouse. https://doi.org/10.3133/sir20135158

Selong, J. H., McMahon, T. E., Zale, A. V., & Barrows, F. T. (2001). Effect of Temperature on Growth and Survival of Bull Trout, with Application of an Improved Method for Determining Thermal Tolerance in Fishes. Transactions of the American Fisheries Society, 130(6), 1026–1037. https://doi.org/10.1577/1548-8659(2001)130<1026:EOTOGA>2.0.CO;2
