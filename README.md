# World Shipping in 1770
This animation provides a 2D visualization of the shipping routes of England, the Netherlands, and Spain in the year 1770, dynamically unfolding through time.

<img src="./ShippingIn1770_gif_640x720p(3).gif" img alt = "Shipping in 1770 GIF"/>

## How It's Made:

**Tech used:** ArcGIS Pro

The data was downloaded and I opened the map. In the Properties of the Ship Positions layer, in the Time tab I selected the Filter Layer Content Based on Attribute Values and also confirmed the parameters of Layer Time that Each feature has a single time field and the Time Field as ShipDate. After confirming the settings, the time slider appears showing the time from 1/1/1770 to 12/31/1770. On the Time tab, I checked the Time Snapping Box in the Snapping group and set the units to Days. I then set the Span to 7 days, which causes the time slider to jump ahead by one week. I then turned on the Colonial Ports and Ship Paths layers in the Contents pane. The way the map looks currently is too bright which is putting up way too much stimulus to be able to see everything on the map properly. In the Effects group, the transparency was changed for the Colonial Ports layer as 50% and 90% for the Ship Paths layer. Now the Ship Positions appear more prominently and the paths and ports are less prominent. The next step is changing the background color to a dark gray that permeates throughout the entire map. In the Map Properties, I set the color to custom gray.

Next up is creating temporal keyframes to show changes in ship positions over the course of a single year. I first definined the change in temporal extent for each time step, which will become the first keyframe in the animation. In the Time tab, in the Current Time group, I verfied that the Spans is set to 7 days and locked it to maintain the seven-day duration and verfied that the Start field is set to 1/1/1770. Then in the View tab, in the Animation group, I clicked the Add Animation button to open the Animation Timeline pane. I then clicked the Create First Keyframe, then in the Export group clicked Movie to open the Export Movie pane. I clicked the Twitter preset, but in this case, I used the Youtube preset instead to allow for a wider resolution that I couldn't achieve with the Twitter preset. I panned the map so that Antarctica was at the base of the frame with a small area of blank space at the top to put the title.

## Optimizations

The resolution could be slightly shorter, as the empty space risks breaking immersion. However, it could also be seen as part of the setpiece, ultimately making it inoffensive in the long run.

## Lessons Learned:

No matter what your experience level, being an engineer means continuously learning. Every time you build something you always have those *whoa this is awesome* or *wow I actually did it!* moments. This is where you should share those moments! Recruiters and interviewers love to see that you're self-aware and passionate about growing.

## Repositories
**Profile:** [T3ch12et](https://github.com/T3ch12et)

**Cartography Repository:** [ESRI MOOC Cartography](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography)

**Main Repository:** [GIS Data Science Portfolio](https://github.com/T3ch12et/GIS-Data-Science-Portfolio)

## Examples:
Take a look at these couple examples that I have in my own portfolio:

**Miami Sea Level Rise:** [3D Miami Beach Sea Level Rise](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/3D-Miami-Beach-Sea-Level-Rise) 

**Athens Heat Risk Index:** [Athens Heat Risk Index](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Athens-Heat-Risk-Index) 

**Oso Mudslide:** [Oso Mudslide](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Oso-Mudslide) 

**Hurricanes since 1851:** [Hurricanes since 1851](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Hurricanes-since-1851) 

**Coral Reef Dashboard:** [Coral Reef Dashboard](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Coral-Reef-Dashboard)

**Rondonia Land Cover Change:** [Rondonia Land Cover Change from 1992 to 2020](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Rondonia-Land-Cover-Change)

**Addressing Climate Change:** [Using GIS to address climate change](https://github.com/T3ch12et/GIS-Data-Science-Portfolio/blob/main/ESRI-MOOC-GIS-for-Climate-Action/Addressing-Climate-Change/README.md)
