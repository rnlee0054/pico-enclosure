# Android Things Pico Enclosure

## [3D Design files (STL)](https://github.com/rnlee0054/pico-enclosure/tree/master/3D)

## The Enclosure!

Images of the 3D printed enclosure (used Type A Series 1 Pro printer and PLA filament).

<img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/IMG_20171009_084340.jpg" width="200" /> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/IMG_20171009_084913.jpg" width="200"/> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/IMG_20171009_083938.jpg" width="200"/>

## Strategy

This project required searching the web for the [Android Things Pico board dimensions](https://shop.technexion.com/pico-pi-imx6ul.html?SID=r9g3e9gt8kt70r9akj784lqrs6) as well as finding inspiration on sites such as [Grabcad](https://grabcad.com/library).
The design goal was to make it as small as possible while having some tolerances ~1mm just in case; a USB port was also required.
The process required learning Fusion 360 and Type A Cura / Type A usage from no prior knowledge.
Modeling loosely followed the top-down approach, starting with the top view and setting constraints and projections to link views together for easier management.

The bottom container was developed first.
The mounting screw holes are of similar style to the Pico laser-cut plywood board, which called only for M2.5 screws instead of self-tapping screws.
This allowed me to reuse the Pico plywood board assets since I was not able to get more self tapping screws.
After working on the top lid, I start designing the snap fits, which required going back to the bottom container and adding the appropriate holes into the side.
In the end, the design was double-checked to make sure the measurements were correct in theory.

## CAD images

### Bottom half (container)

<img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-54-31.png" width="600" />

Top | Front | Right
---|---|---
<img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-51-14.png" width="200" /> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-48-49.png" width="200"/> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-50-31.png" width="200"/>

### Top half (lid)

<img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_03-00-21.png" width="600" />

_Note the lid above is upside-down, displaying the snap fits_

Top | Front | Right
---|---|---
<img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-59-01.png" width="200" /> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-57-12.png" width="200"/> | <img src="https://github.com/rnlee0054/pico-enclosure/raw/master/Images/Fusion360_2017-10-08_02-58-24.png" width="200"/>
