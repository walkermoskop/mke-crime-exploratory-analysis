# mke-crime-exploratory-analysis
A series of data visualizations of MKE pre/post pandemic crime trends.

Files included:
 - data-processing.ipynb: Simple downloading and processing of crime data. To replicate, weather data would need to be downloaded from [this NOAA search tool](https://www.ncdc.noaa.gov/cdo-web/search). I used daily temperature summary data dating back to 2012 from Gen. Mitchell airport in Milwaukee. I included the following daily-level fields: high temperature, snowfall, snow depth and precipitation.
 - time-series-analysis.ipynb: Visualizing totals for various types of crime over time.
 - time-series-model.ipynb: Builds a model to forecast what crime levels could have been under more "typical" circumstances (i.e. no pandemic).
 - mapping.ipynb: Lots of geographic visualizations of everything from homicides to auto thefts.
 - mapping.html: HTML output of above file (which won't fully load on github).