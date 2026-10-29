Reflective Analysis:
This map is intended to display data relating to low-income populations and their ability to access supplementary food sources, 
outside of grocery stores. While it does not provide a complete picture, it could be one source in a larger data set used by the city, 
non-profits, or other social services organizations, to analyse where in the city these resources might be needed the most. However, 
it does risk being misleading in two ways: first, the division of the Census data was done manually, as there were technical issues 
trying to produce a histogram using ArcPro and QGIS; and second, community gardens and fruit trees are not necessarily available food 
sources for low-income populations, according to research done in GEOG350
(https://wiki.ubc.ca/Course:GEOG350/2026/Food_Security:_Community_Gardening_in_One_of_Vancouver%27s_Most_Vulnerable_Neighbourhoods). 

A single-hued scheme was selected for the census data as it is a choropleth map; warm tones were chosen to have the highest contrast 
with the blues, greens, and yellows initially present on the map. The opacity was higher at lower zoom levels so the census DAs would 
stand out, and reduced at higher zoom levels so that the block structure could be seen when the user examines a particular data point. 
The colours of the point data were selected to have contrast to each other and the census data, and green was avoided to reduce 
accessibility challenges for colourblind users. The opacity was lowered to ensure that both point data would be visible even when 
they overlapped. The water was changed from blue to grey to reduce visual competition with the census DAs, and much of the greenspace 
layers such as parks, cemeteries, landcover-wood, landuse-pitch, etc. were made more transparent and higher zoom levels. Roads, 
bridges, and other infrastructure layers were removed or reduced in opacity as navigation is not the purpose of the map.

Two key ways to update this map in the future would be to would add pop-up data about each of the point data, and to find a more 
analogous colour scheme and make stylistic choices that better conveyed the topic, as this map does not do so satisfactorily. 

Link to map:
https://rosenorth9638580.github.io/rosenorth9638580-web/exploratory-lab-1/index.html

Image:
![alt text](https://rosenorth9638580.github.io/rosenorth9638580-web/exploratory-lab-1/lab-1-screenshot.png"rosenorth9638580_screenshot")

Collaboration:
Professor Bergmann's assistance was crucial in helping me overcome the technical barriers during the data collection and 
web hosting portions of this lab, and I would not have been able to reach the styling portion without it. Lila Jones was of 
great assistance as well. We shared frustrations, and they helped me problem solve by reminding me to use the console to check 
for errors and suggesting what they had done to overcome their issues. They did ask me about some of their challenges but 
unfortunately, I was not able to provide much technical assistance. Two key areas they helped with were in reminding me how 
to make the colour gradient for the choropleth map in Maputnik, and how to make the legend using CSS in index.html rather than 
using JS. They also provided feedback regarding my colour scheme, which prompted me to turn down the opacity on several more 
layers, particularly the green spaces such as landcover-wood, parks, cemeteries, etc.  No generative AI was used at any stage 
of this project. 
