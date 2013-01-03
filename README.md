# Compound Cities

While *compound city* isn't a proper geographic term, it is a fitting description for large cities with multipe well-defined and sometimes semi-autonomous administrative sub-divisions.  For example New York is composed of 5 *boroughs*, and Tokyo is a vast conglomerate of 23 *special wards* as well as numerous cities, districts, and subprefectures.  It is often hard to find machine-readable data on the boundaries of these sub-divisions, and rarely are such data ever organized to highlight the logical hierarchy of the areas.  This repository aims to collect boundary polygons for such compound cities.  Currently it contains administrative boundary geoJSON data for:

- New York City
- London
- Tokyo

FeatureCollections of the compound city subdivisions have been split into multiple files (one per the features of each subdivision).  So for example for Greater London, there is a three level heirarchy with boundary files avaialbe for entities at each level of the heirarchy.

- Greater London
	- Inner London
		- Camden
		- Greenwich
		- Hackney
		- Hammersmith and Fulham
		- Islington
		- Kensington and Chelsea
		- Lambeth
		- Lewisham
		- Southwark
		- Tower Hamlets
		- Wandsworth
		- Westminster
		- City of London
	- Outer London
		- Barking and Dagenham
		- Barnet
		- Bexley
		- Brent
		- Bromley
		- Croydon
		- Ealing
		- Enfield
		- Haringey
		- Harrow
		- Havering
		- Hillingdon
		- Hounslow
		- Kingston upon Thames
		- Merton
		- Newham
		- Redbridge
		- Richmond upon Thames
		- Sutton
		- Waltham Forest

# Data Sources an License

### New York City Boundaries 

http://www.nyc.gov/html/dcp/html/bytes/meta_dis_nyborough.shtml

### Greater London 

http://www.ordnancesurvey.co.uk/oswebsite/products/boundary-line/index.html
http://www.ordnancesurvey.co.uk/oswebsite/docs/licences/os-opendata-licence.pdf

### Tokyo

http://www.esrij.com/products/data/japan-shp/

ESRI Japan, via The Ministry of Internal Affairs and Communications and The Ministry of Land, Infrastructure and Transport.



