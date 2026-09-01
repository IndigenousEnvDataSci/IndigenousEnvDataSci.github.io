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

## Learning goals:

1. Understand how to interact with data in R, starting with bringing data into the computing environment to explore 
2. Calculate and interpret the middle values (mean, median) and extreme values (min, max) of a dataset
3. Create straightforward plots to visualize safety thresholds and communicate results with the community 
4. Apply both statistics and visuals to determine if local fish are safe for consumption

## Note for instructors: 

This module also comes with a student worksheet, which can be printed or made available to students online. [Link to worksheet for Module 1](https://github.com/IndigenousEnvDataSci/EJ-DS/blob/main/Worksheets/Module%201_%20Monitoring%20Fisheries%20for%20Heavy%20Metal%20Contaminants.pdf). 

Data used here is 'dummy' data created based on a study that measured and related fish size and mercury concentration (Somers and Jackson, 1993).
See the file [fish_data_dummy.R](https://github.com/IndigenousEnvDataSci/EJ-DS/blob/main/Mod1_Fish/fish_data_dummy.R) for more information on how it was created or to make your own adjustments. 

**References**

Keith M. Somers and Donald A. Jackson. 1993. Adjusting Mercury Concentration for Fish-Size Covariation: A Multivariate Alternative to Bivariate Regression. Canadian Journal of Fisheries and Aquatic Sciences. 50(11): 2388-2396. https://doi.org/10.1139/f93-263

Technical Information on development of FDA/EPA advice about eating fish for those who might become or are pregnant or breastfeeding and children ages 1-11 years | FDA. (2024). https://www.fda.gov/food/environmental-contaminants-food/technical-information-development-fdaepa-advice-about-eating-fish-those-who-might-become-or-are 

