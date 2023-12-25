# bbs-R_viz
RShiny app to visualise abundance data from the Breeding Bird Survey

The North American Breeding Bird Survey is 'a long-term, large-scale, international avian monitoring program initiated in 1966 to track the status and trends of North American bird populations. The USGS Eastern Ecological Science Center and Environment Canada's Canadian Wildlife Service jointly coordinate the BBS program.' [title](https://www.pwrc.usgs.gov/bbs/about/).
There's certain limitations inherent to the survey on account of its design.
Significant efforts have been invested generate models and predictions of abundances based on the at-times lacunary information. Such index data can be plotted to view changing popualtion trends. This R Shiny app allows the user to manipulate various variables to view maps and graphs for specific species.

- The processed index prediction datasets were pulled from: [USGS](https://www.usgs.gov/data/north-american-breeding-bird-survey-analysis-results-1966-2021) 
- Species list obtained from: [here](https://www.sciencebase.gov/catalog/item/64ad9c3dd34e70357a292cee)
- Bird Conservation Regions (BCRs) shapefiles from: [Bird Studies Canada and NACBI](https://www.birdscanada.org/bird-science/nabci-bird-conservation-regions)
