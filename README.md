Road Maps using OSM Data and ggplot2
====================================

The 'Mapping' RMarkdown File included here uses R code based on the [excellent tutorial](https://ggplot2tutor.com/streetmaps/streetmaps/ "ggplot2tor - StreetMaps") written by Christian Burkhart

We're going to use the {osmdata} package to access Open Street Map Data and plot lines using {ggplot2}.

### The General Process
1. Load in the packages: osmdata, tidyverse (for ggplot2, magrittr etc) and beepr*
2. Create objects for large streets, small streets and rivers for plotting later
3. Plot!
4. Save the plot

##### **I love the beepr package. Some of the processes take a while if you're getting data from a large area, or plotting/saving at a large size/high detail. beepr has one function which you add to the end of your code. Once completed, it will play a sound effect so you know it's finished.*

### Some Examples

Aberdeen

<img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/Aberdeen.png?raw=true" width="500" height="500"><img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/AberdeenDark.png?raw=true" width="500" height="500">

Dublin

<img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/Dublin.png?raw=true" width="500" height="500">

Galway

<img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/GalwayDark.png?raw=true" width="500" height="500">

Edinburgh

<img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/Edinburgh.png?raw=true" width="500" height="500">

Lusaka

<img src="https://github.com/will-ball/OSM-RoadMaps/blob/main/Plots/LusakaDark.png?raw=true" width="500" height="500">
