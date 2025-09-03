(mod_kav)=
# [Water Quality and TEK](https://github.com/IndigenousEnvDataSci/WaterQuality_mod1)

The modules on this site are based on a fictional tribe called the K'avi. We needed the tribe to be fictional because we did not want to focus on any indigenous groups that I teach. The location is also fictional, but representative of a place with ample surface water, a high elevation stream network fed by glaciers with wetlands and a lake. Data is similar to data that has been collected in Western Montana, but for the purpose of these activities, we use 'dummy' data created for these modules. 

Throughout this modulel, we reference sample locations, which are labeled in blue in the map, and cultural sites, which are labelled in green in the map below. Water quality samples were taken at all five sites, and these are compared across sites and with the closest cultural site. 

![](../images/K_aviTribeMap.png)

## Module Learning goals:

1. Compare water quality across different sites based on multiple metrics 
2. Reflect on how including TEK values can affect the outcome of prioritizing locations
3. Describe how a 'tidy' dataframe in R is formatted, and be able to read in a CSV and check whether it is tidy, and how to change it if not 
4. Visualize and create plots, differentiating when to use histograms, time series, boxplots, and scatter plots

## Data science topics: 

All parts include:

- Reading in a CSV file, previewing, editing and saving as a new dataframe 
- Using `ggplot2` to plot using different geoms 

[Part 1: Intro to K'avi Tribe Water Quality](Kavi_pt1.ipynb)

- tidying data (removed unnecessary columns, filtering out rows with repeated header)
- grouping and summarizing data by year
- data visualization with ggplot2 - time series and boxplot

[Part 2: Visualizing TEK](Kavi_pt2.ipynb)

- using `pivot_longer()` function to reformat data
- creating boxplots and point plots with standard errors
- summarizing data by site and use `inner_join()` to combine with other data frame 

[Part 3: Water Quality Rating](Kavi_pt3.ipynb)

- creating up checks using `ifelse()` with conditionals about water quality 
- summmarizing each site by the percent of samples that pass test 
- joining data frames using `inner_join()` by sample location

[Part 4: Bacteria and Nutrients](Kavi_pt4.ipynb)

- manipulating data frame 
- summarizing data by categories 
- checking for conditionals using `ifelse()`

## Note for instructors: 

This activity is also available as Rmarkdown files and with CSV files at this [github link](https://github.com/IndigenousEnvDataSci/WaterQuality_mod1). The first two parts were used for a day-long workshop at AIHEC 2024.  

## Acknowledgements 

This activity was first created by Georgia Smies at Salish-Kootenai College, and developed by Helena S. Kleiner at University of Notre Dame. It was later modified by Cazimir Kowalski, also from University of Notre Dame. 