# sacramento-daycare-map
This project is a map of daycare facilities in Sacramento County derived from the California Department of Social Services licensing data. This does not include home daycares, for which only  the facility zip code data were available. Data are current as of 9/1/2019.
- Downloaded daycare data from https://secure.dss.ca.gov/CareFacilitySearch/DownloadData
- Filtered this dataset to only facilities in Sacramento County
- Converted addresses into latitude/longitude coordinates using Texas A&M's free geocoding resource http://geoservices.tamu.edu/Services/Geocode/
- Created a web map using leaflet
