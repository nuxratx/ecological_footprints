# ecological_footprints
Recreating world map measuring the human demand on natural capital. Inspired my Kimberly Fessel. Creating a web map from data with Python folium.This choropleth displays the ecological footprint of countries of the world, where the numerical values represent global hectares per capita, or gha. For quick reference, our planet can recoup about 1.6 global hectares per person, so countries exceeding 1.6 gha operate at a resource demand level that’s eventually unsustainable. 
In order to make this map in Folium, I first created a base map for the world and selected web tiles. Then I updated the starting location and zoom level for an appropriate view of the world. Fianlly adding boundaries for each country through GeoJSON data, and then you’ll add a choropleth layer based on ecological footprint data. 

#Getting resources: 
I used Natural Earth project's geojson.xyz services. Go here >  https://geojson.xyz/ > scroll to find > admin 0 countries <url>
Then I got my data from wikipedia -> https://en.wikipedia.org/wiki/List_of_countries_by_ecological_footprint -> convert the data into a csv

![world](https://github.com/nuxratx/ecological_footprints/assets/161661618/3cdf6b94-1cc5-4745-b07c-b558a3bb067d)

