# [Module 3: Bison reintroduction and plant biomass](https://github.com/IndigenousEnvDataSci/EJ-DS/tree/main/Mod3_Bison)

For many years, the K'Avi tribe has had cattle grazing pastures throughout their land. Cattle have been a useful agricultural resource, but they are not native to the K'Avi's region. In the past year, tribal agriculture managers have noticed a decreased vitality in many of their grazing lands causing less regrowth and a decrease in native plant species. This is most likely due to the cattle, as they are non-specific grazers and are a non-native species. Tribal agriculture managers are considering reintroducing bison to the lands for both ecological and cultural reasons. Bison are native to this region and have been observed to increase native grass species richness by 103% in comparison to cattle! Reintroducing bison will also re-establish the K'Avi's cultural and historical connections to the land, and can reaffirm food sovereignty and provide additional economic benefits. The managers are hoping to repurpose the cattle grazing lands to become bison grazing lands to foster a more sustainable agricultural practice for the region and to ensure the preservation of the native grasslands.

In collaborations with numerous tribal governments, K'Avi agriculture managers are hoping to transfer a herd of 200 bison for reintroduction, which would allow for genetic diversity within the herd and opportunities for sustainable hunting. 

To reintroduce bison, the land must have enough available sustenance for the bison to graze and maintain a healthy lifestyle. The tribal agriculture managers are considering three sites for reintroduction and have produced a dataset (`biomass.csv`) with the annual plant biomass (i.e., the amount of food available) at each site. They also used GIS to calculate the area of each site in hectares (one hectare is roughly equivalent to two football fields), producing the dataset `bison_sites.csv`. These data will help determine which sites are viable for bison reintroduction! While the hope is to eventually reintroduce bison herds to all of these sites, K'Avi agricultural managers must currently choose a single site to place this first herd of 200 bison. 

## Data science topics covered:

-   Loading and previewing data from CSV files
-   Grouping and summarizing data 
-   Joining data frames by site ID 
-   Creating new columns with `mutate`
-   data visualization with `ggplot` : bar plots

## Learning goals: 

1. Learn to combine separate data sources into a single, cohesive dataset
2. Group data by specific categories (in this case field sites) to summarize and explore side-by-side comparisons
3. Standardize and convert different units of measurement to make data easier to interpret and compare
4. Evaluate multiple environmental variables simultaneously for managing decisions on reintroducing native species to their habitats

## Note for instructors: 

This module contains optional extra steps towards the end, which re-do the analysis with the additional consideration of elk populations in the area.

**Sources for bison and elk diet:** 

The citations for this are stepwise -  First, evaluate the protein content of different forage types.  Next, evaluate the ability to metabolize nitrogen from protein in the forage, and finally evaluate seasonality in forage types.  Here are the citations:

Van Soest, P. J. (1994). Nutritional Ecology of the Ruminant. Cornell University Press.
  - This book discusses nitrogen requirements in ruminants and how dietary crude protein (CP) relates to nitrogen intake.

National Research Council (NRC) (2000). Nutrient Requirements of Beef Cattle. National Academies Press.
  - While focused on cattle, the NRC guidelines provide estimates for protein requirements in large ruminants, which can be adapted for bison.

Schwartz, C. C., & Hobbs, N. T. (1985). "Forage and range evaluation for bison in Yellowstone National Park." The Journal of Wildlife Management, 49(2), 407-413.
  - Discusses bison diet composition and forage quality, which affects nitrogen intake.

Renecker, L. A., & Hudson, R. J. (1986). "Seasonal energy expenditures and thermoregulatory responses of moose." Canadian Journal of Zoology, 64(2), 322-327.

Christopherson, R.J., Hudson, R.J., & Christophersen, M. (1979). SEASONAL ENERGY EXPENDITURES AND THERMOREGULATORY RESPONSES OF BISON AND CATTLE. Canadian Journal of Animal Science, 59, 611-617.

