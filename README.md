# Buncombe_GV

### Interactive Map of Buncombe County North Carolina with Gunviolence incidents displayed as points and median income displayed as a chloropleth base layer. 

### The main interactions of this map are 
  + Gun Violence incidents displayed at the point level
    + The points are scaled based on the total number of victims of the incident (total fatalities + total injured)
    + The point symbols differ if there were or were not fatalities in the incident (skull representing a fatalitiy while the bandaged person means there were only injured people
    + The points can be clicked on to display more information about the incident
  + The layer can be filtered and toggled in the top right to filter out injured, killed, or toggle the chloropleth
  + Time Slider
    + Utilizing the dates attached to each incident to allow for filtering based on year
    + When scrubbing through the years a chart is also made to show the distribution of the crimes by month

### Data Sources
##### The data for this map came from the gun violence archive, this dataset goes from 2014-2023 and includes data for the entire country. For my use case it was processed and filtered in RStudio to just Buncombe county. 
##### Data for the chloropleth base map was acquired from Social Explorer using the American Community Survey's latest dataset at the block group level. This dataset was then joined with a shapefile for the block groups to create the chloropleth.

### Libraries Used
 + Leaflet CSS and JS
 + Font Awesome
 + Chroma JS

