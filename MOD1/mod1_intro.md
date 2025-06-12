(mod1)=
# [Module 1: Monitoring fisheries for heavy metal contaminants](https://github.com/IndigenousEnvDataSci/EJ-DS/tree/main/Mod1_Fish)

Members of the K'avi have fished the waters on their land for many years to provide food for their community. To manage these waters, K'avi tribal fishery managers have been monitoring fish growth rates across the local water bodies in their community. 

However, many members of the community have begun to experience health problems associated with heavy metal poisoning. Historically, a factory used to be located upstream of the riverways fished by the K'avi, and waste from this factory was dumped into the nearby waters. Tribal fishery managers are now concerned that members of the community are being exposed to heavy metals, like methylmercury, through the fish that have been caught in these waters. As a result, they now want to start recording the concentrations of methylmercury (mercury) in the belly fat of fish in the area. The tribe uses guidance from the Environmental Protection Administration (EPA), who have determined a Reference Dose (RfD) of mercury at 0.1ug per kg of body weight. 

Additionally, the Food and Drug Administration recommends eating no more than 0.46ug methylmercury/g of fish within a week ([FDA](https://www.fda.gov/food/environmental-contaminants-food/technical-information-development-fdaepa-advice-about-eating-fish-those-who-might-become-or-are)). Health hazards depend on how much fish a person consumes as well as their size, so the RfD could range between 0.15ug to 0.46ug. These values are explored more in the code.  

Back in 1998, the tribal fisheries managers caught fish and measured their length and also the concentration of mercury in the fish. The goals of these managers was to learn how common it was for concentrations of mercury to be above a safety level of 0.46ug/g.

Once they collect these data, the tribal fishery managers will need to present their findings to members of the community so they can better understand the public health crisis at hand. 

## Data science topics covered: 

- Using R for math 
- summarizing data
- scatter plots 
- data visualization with `ggplot`

## Module goals:

1. Explore data related to fish length and heavy metal concentrations.

2. Summarize data relative the safety thresholds of mercury concentrations.

3. Create a graph that could be used to communicate the fishery managers' findings to their community. 

## Learning goals:

1. Students become more comfortable opening R and loading in data from an 
external data file. 
  
2. Students gain exposure to basic commands to explore their data before 
they begin to analyze it. 

3. Students gain experience loading in packages (`tidyverse` and `ggplot`). 

4. Students gain exposure to working with different data types (numeric, characters)

5. Students gain exposure to basic summary statistic arguments in R to pull the 
mean, median, max, and min values for different variables in the dataset. 

6. Students become equipped with how to make a graph in R using `ggplot` 
with variables pulled from a larger dataset. Can open a discussion point: 
how do we present data in a way that can help us understand the problem at hand?
(i.e. in this case, it may be plotting mercury concentrations found in fish 
at different times, or finding a realtionship between mercury concentration and fish length)

## Note for instructors: 

Data used here is 'dummy' data created based on a study that measured and related fish size and mercury concentration ([Somers and Jackson, 1993](https://jackson.eeb.utoronto.ca/files/2012/10/Somers-and-Jackson-1993.pdf)) See the file [fish_data_dummy.R](https://github.com/IndigenousEnvDataSci/EJ-DS/blob/main/Mod1_Fish/fish_data_dummy.R) for more information on how it was created or to make your own adjustments. 


