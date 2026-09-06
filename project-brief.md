#My project brief
##The Question
Which wards in Kaduna South Local Government Area, Kaduna State,are more than 5km from a health facility?
#Why it matters
Kaduna South sits on the edge of Kaduna metropolis, 
with settlement spreading outward from the city while other wards stay rural. 
A ward-level view of facility gaps could help the LGA health department, 
or an NGO planning outreach,
decide where a new primary health centre or mobile clinic would help outreach, 
decide where a new primary health centre or mobile clinic would help the most.
#The data I need
Ward boundaries- Kaduna South LGA, Kaduna State
Health facility locations- Kaduna State, points
Roads- Kaduna South LGA,for context now and a possible travel time upgrade later
#Where each dataset comes from
Ward boundaries- GRID3 NGA 
Operational Wards v3.0-
https://data.grid3.org/datasets/GRID3::grid3-nga-operational-wards-v3-0/explore - GeoPackage, statewide,filter to Kaduna South
Health facilities- GRID3 NGA 
Health Facilities v3.0- search 'Nigeria health facilities' at https://data.grid3.org- GeoPackage,statewide, clip to Kaduna South
Roads- OpenStreetMap, extracted with the QuickOSM plugin in QGIS- no separate download link, pullled directly for the Kaduna South extent
#What I would build
A map of Kaduna South showing which wards fall morethan 5km from a health facility, 
with the uncovered areas shaded. 
Longer term this could become a small dashboard for the LGA health department, 
and the straight-line distance could be upgraded to real travel time once I have a road network with speeds.