# houston_health_insurance_viz
A repository for data &amp; code related to Houston data visualization meetup data jam on health insurance coverage or lack of in Houston

## Data

Data is in the folder data.

#### nhgis0001_csv
Inside of the data folder is the nhgis0001_csv folder that contains a CSV file of insurance data for Texas on census block group level. The data dictionary text file describes all the columns in the data file. This data file was downloaded from https://data2.nhgis.org/main which is a service that provides a variety of census and other data. 

<i>That data comes with <a href="/data/nhgis0001_csv/file_limits_and_citation.md">the following citation and limits</a>.</i>

#### Spatial shape file for Census block group and tract boundaries across state of Texas
Inside the `data/cb_2018_48_bg_500k/` folder



---- notes:
http://geospatialpython.com/2010/12/subsetting-shapefile-by-attributes.html


---
## 


## Data Preparation
In order to relate the cb_2018_48_bg_500k spatial shapefile and the nhgis0001_csv excel file together, I had to convert several integer fields for state, county, census tract, and block group into strings and then concatenate them together into a single field. This then ends up being the same thing as the geoid field in the shape file. 



## Data Visualization
I've quickly thrown these into tablea public and merged the two data sources on the basis of the geoid field in the shape file and the concat_statecountycensustractblock field in the excel file. 

I then could start to build data visualizations in tableau with the data.



tbd


## Related Text Context

tbd
