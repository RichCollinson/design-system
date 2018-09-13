---
layout: default
section: Patterns
title: Location map
---
# Location Map
***
## What is it?
Presents the customer options top provide a location
Used for capturing the location of any point of public space within the CoM boundary.
Customer can choose between using a map or typing an address.
Screen flows below show both options under 'how does it work?'
## How does it work?
## Find on map

### Provide a location using THE MAP

__Method of providing location or address__
Customer is presented with option to provide a known address or location.
__Buttons__
If the screen is the first step in the form, then one button spanning the full width is used - as above.
If the module is a step in the middle of a form flow, then 'Back' and 'Next' buttons are shown.

![](img/find_on_map.png)



### Full screen map - Move map location to pin

__The full screen map__
On selecting 'Find on map' a full screen map is displayed, with a centered pin. 

On interaction the the map is movable, the pin remains static. 

__Location services__
If location services ON (example above)
'Go to current location' button IS displayed above the 'Back' and 'Confirm' buttons. 

__If location services are OFF__ 
'Go to current location' button IS NOT displayed above the 'Back' and 'Next' buttons. 
The map location defaults to the town hall.

Selecting 'Back' takes the user back to the previous step. 

Selecting 'Next' takes the user to step 3 __'Confirming the data provided'__ 

![](img/find_on_map_2.png)


### Optionally add location detail

__Confirming the data provided__
This step serves as a check point to review the location they have provided and an opportunity to provide additional written information about the location. 

__Edit button__
Selecting 'Edit' opens the map full screen again.
-map image displays
-__NO__ location description displays
And the customer can click 'confirm' to continue through the form

![](img/find_on_map_3.png)

## Type an address

### Provide a location using THE ADDRESS MATCH 

__Method of providing location or address__
Customer is presented with option to provide a known address or location.
__Buttons__
If the screen is the first step in the form, then one button spanning the full width is used - as above.
If the module is a step in the middle of a form flow, then 'Back' and 'Next' buttons are shown. 

### Matched addresses

__Address matching__
Address input field on typing 5+ characters will attempt to match the typed address string

### Selection made

## Where is it used?

| Service        | URL (Please note these are DEV URLs)           | Used?  |
| ------------- |-------------| -----|
| Graffiti      | https://dev01.dev.services.melbourne.vic.gov.au/report/graffiti | Yes  |
| Tree Maintenance | https://dev01.dev.services.melbourne.vic.gov.au/report/treemaintenance | Yes - Private trees part of the flow only    |
| Abandoned Vehicle | https://dev01.dev.services.melbourne.vic.gov.au/report/abandonedvehicle     | Yes     |
| Illegally Parked Vehicle | https://dev01.dev.services.melbourne.vic.gov.au/report/illegallyparkedvehicle     |  Yes   |
| Syringe Management | https://dev01.dev.services.melbourne.vic.gov.au/report/syringemanagement     | Yes    |
| Illegally Dumped Rubbish | https://dev01.dev.services.melbourne.vic.gov.au/report/illegallydumpedrubbish      |  Yes   |
| Rough Sleeping | https://dev01.dev.services.melbourne.vic.gov.au/tellus/online     | Yes    |
| Parking Infringement Review | https://dev01.dev.services.melbourne.vic.gov.au/ask/infringementreview     |  No   |
| Animal Infringement Review | https://dev01.dev.services.melbourne.vic.gov.au/ask/animals/infringementreview     | No   |
| Local Law Infringement Review | https://dev01.dev.services.melbourne.vic.gov.au/ask/locallaws/infringement     |  No   |
| General Enquiry |  https://dev01.dev.services.melbourne.vic.gov.au/ask/question    |   No  |


