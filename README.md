# MLFinalProject
Final project for STATUN3106

In 2023, the federal government intervened in negotiations over water usage in the lower Colorado River basin in order to prevent extreme drought conditions from entirely depleting critical reservoirs. This project takes precipitation data from across the country and analyzes the last 30 years of data in order to identify regions that may be experiencing trends similar to regions in the river basin. In order to achieve this, a hierarchical clustering model is used and clusters are compared to one another and clusters containing the drought-afflicted regions are identified.

NOAA data is available online and the code will automatically retreive them. URLs in the code may not run if the data has been updated. In that case, the relevant repository is here: https://www.ncei.noaa.gov/pub/data/cirs/climdiv/

Climate region names are not available as a dataset and must be encoded by hand in a separate csv file. The relevant information is here: https://www.ncei.noaa.gov/access/monitoring/reference-maps/conus-climate-divisions
