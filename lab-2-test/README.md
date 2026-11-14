Bee Species of British Columbia

This map was designed for a member of the general public who might have an interest in bees in British Columbia. 
It is not designed to make a particular argument, but rather for the user to explore the bee occurrence data and 
make their own inferences about their location, habitat, and other factors present on the map. To improve the map, 
future data about the following could be incorporated: agricultural lands, air pollution, communication tower 
locations, and more. Additional winged pollinators could also include honeybees, butterflies, and moths. 
Additionally, if hosted by a platform with a larger file limit, higher quality tiles could be used. 

To design this map, occurrence data for the bees was downloaded from GBIF.org, using data from iNaturalist. 
The species were selected from a list provided by Bees of Canada (https://www.beesofcanada.com/species). The land 
cover data was from Natural Resources Canada accessed via the Open Government Portal, and the hillshade terrain 
data contains information licensed under the Open Government Licence via AWS Open Data. These data were clipped to 
the shape of BC using a BC boundary file from StatsCan via @ljones47. The raster data were converted into PMTiles. 
Maputnik was also used to style the basemap and incorporate road and city data. Adobe illustrator was used to extract 
hex codes for the raster band colours. An earlier version of the map was designed without a base map, but without 
such it lacked any grounding in the real world. Adding a basemap makes it easier for the user to orient themselves 
to the map and understand the broader context beyond the data. 

Layers and labels for highways and cities were included to help the user orient themselves when viewing at a smaller 
scale, and airports, railways, city details, and streets were included for when the user might zoom in on an urban area. 
As the point data is occurrence data, the user might be able to make some inferences about why the data is located 
where it is and how it might be collected, given the surrounding land use and transit routes. The basemap was kept 
cool toned and desaturated to help it visually recede, while the tile and point data are vibrant to draw the user’s 
attention. Transparency was added to the point data to help the user decern between overlapping instances. The colour 
of the land cover types were kept the same as the original data source to keep with conventions and help the user 
associate the colour with the data type more readily. A golden yellow colour was initially chosen for the point data; 
however, this was not very visible on grassland and cropland terrain. It was then changed to a warm purple shade, but
in hindsight this does not have sufficient contrast with the red of urban areas, where many of the bee data are congregated. 

There were two interactive goals for this map. The first was to have the species name and event date appear as a hover on 
mouseover of a bee occurrence, with the more ambitious goal of including a photo when the instance had image data available. 
The second interactive goal was to have a buffer appear on mouse click, around all of the same species as the point that 
was clicked. This buffer could help the user identify the general distribution of different species of bee. However, this
interface style would limit the user by their device, as mouseover events are not compatible with touch screens. This 
could be modified to have the buffer appear by a selection filter rather than mouse click, and have the mouse click reserved 
for the popups. Unfortunately, neither mode of interactivity was fully implemented by the deadline. 

Collaboration:
@ljones47 was extremely helpful in troubleshooting provided information about errors they had run into that might be related 
to my errors. I provided peer feedback on their map and suggested that to resolve the issue of place labels appearing 
underneath their other layers they might be able to reorder the json file via Maputnik or manually. I also suggested they 
use margin on their legend elements to align the legend items. Professor Bergmann’s advice and help with troubleshooting 
was essential. Generative AI was not used at any stage of this assignment. 

Link to map: https://rosenorth9638580.github.io/rosenorth9638580-web/lab-2-test/index.html

Image:
![alt text][screenshot]

[screenshot]: https://rosenorth9638580.github.io/rosenorth9638580-web/lab-2-test/lab-2-screenshot.png "rosenorth9638580 screenshot"

This screenshot of the Smithers area demonstrates how the land cover, elevation, point, and highway data work together to help 
the user understand the possible relationships between these data. 
