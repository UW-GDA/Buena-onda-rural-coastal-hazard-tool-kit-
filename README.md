# Buena-onda-rural-coastal-hazard-tool-kit-
Hello!

Members: Florencia Gonzalez-Martinez and Paulinne Anaya

## Topic Title: Rural Coastal Hazard Mitigation

## Introductory background information: 

Florencia's Capstone Studio Project: Coastal Community Adaptation: Planning and Designing Upland Expansion and Relocation

The current capstone studio project examines strategies for hazard mitigation in rural coastal regions. The scope of work is centered in Washington's Coastal region, especially in Westport and Grayland. As coastal erosion occurs due to intense winter storms, high-engery waves, and other climate related factors. Home owners and communities in the rural coastal areas face the problem of losing their communities and home ownership.

Rural coastal communities are primarily served by county governments, which function as the local governing authority for areas outside incorporated city limits. However, a significant gap often exists between county governments and rural communities due to disparities in resources, limited institutional capacity, and differing local needs. Many rural coastal communities are particularly vulnerable and under-resourced, making it difficult for county governments to adequately serve them. This disconnect can contribute to the decline of rural coastal communities and the deterioration of local economies.

## Short 1-2 sentence summary
Rural coastal hazard mitigation is a critical planning priority. By developing an interactive web mapping tool that can support this effort by enhancing public education and awareness of local hazards and available mitigation strategies. Such a tool can assist both county governments and residents in identifying areas for improvement by visualizing risks related to coastal erosion and flooding.

## Problem statement, question(s) and/or objective(s):
Our objective is to develop an interactive web mapping tool for county governments and residents in identifying areas for improvement by visualizing risks related to coastal erosion and flooding. Tentatively we are considering looking at Washington coastal communities of Westport and Grayland and would like to compile 19 year tidal data and satellite images of the coastline to map shoreline change due to erosion. To get a better understanding of communities that are affected by coastal erosion and flooding a layer showing census data will display demographics impacted.

## Datasets you will use (with links, if available)
The datasets we will use are broken down from LiDAR to Flood Fraquency from NOAA to protray interactive changes in the coastal land in the 19 year time frame. An overlay of census data and coastal total economy data from NOAA for demographic analysis to get understanding of who is being affacted. 
* Here is the census data for [Harbor County, Washington](https://data.census.gov/table?q=Grays+Harbor+County,+Washington&y=2000)
* Here is Coastal LiDAR data for [Harbor County, Washington](https://coast.noaa.gov/dataviewer/#/lidar/search/-13856847.26738303,5908019.272588322,-13710174.710064648,6029677.328139233)
* Here is Flood Fraquency for [Harbor County, Washington](https://coast.noaa.gov/slrdata/)
* Here is Total Economy (Coastal) for [Harbor County, Washington](https://coast.noaa.gov/digitalcoast/data/coastaleconomy.html)


## Tools/packages you’ll use (with links)
The tools we will be using is:
- GeoPandas
- Interactive maps
The Packages we will be using is:
- ipyleaflet

## Planned methodology/approach
1. Download and Clean raw data
2. Filter data from NOAA like Flood Fraquency and Total Economy to be located in Grays Harbor County.
3. Choose a Projection and set all the data sets to the same projection
4. Start with creating the 19 year time frame for erasion and flooding data
5. Add a time bar for the interactive elemet of showing erasion and flooding in the site throughout the year.
6. Do some statistical analysis on the census and pull any significant data that overlay with erasion and flooding.
7. Add demographic data as a

## Expected outcomes

## Any other relevant information, images/tables, references, etc.

## References
