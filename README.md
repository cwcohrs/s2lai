# Calculate Leaf Area Index from Sentinel-2 Imagery

A companion R Shiny application for the publication **Cohrs, C.W., R.L. Cook, J.M. Gray, and T.J. Albaugh. (2020). Sentinel-2 Leaf Area Index Estimation for Pine Plantations in the Southeastern United States. *Remote Sensing*. 12, 1406. [link to article](https://doi.org/10.3390/rs12091406)**

Intended to give pine plantation managers in the Southeastern US a simple tool for assessing the LAI of their forests.

A **live version** can be accessed via https://www.treepoet.com/s2lai.

![s2LAI - Example Image](https://static.wixstatic.com/media/eae594_1c856cfa53de4614b6c38b13d1bd506b~mv2.png)

### Features Fully Implemented:
- Upload Sentinel-2 Level-2A Band 4 (red) & 8 (near-infrared)
- Upload shapefiles, representing an Area of Interest (AOI), e.g. either for single of multiple forest stands/sites; explore tabular contents.
- Calculate LAI for either the entire scene, or just clipped to the uploaded AOI.
- Export/Download LAI Output, clipped to the AOI that was uploaded by the user or the entire scene.

### Features Still To Be Implemented:
- Calculate the weighted, mean LAI for each individual observation/polygon within the uploaded AOI dataset; dynamically join to table.
- Add an "Export as CSV" button to download the tabular contents of uploaded AOI, with LAI calculations included for each row/observation/polygon.
- Add a "Save as New Shapefile" button to download the updated shapefile.
- Rendered plot interactivity (e.g. dynamically updating values as user moves cursor across the plot)
- A **stand-alone, local desktop version** is planned.

----

Need Sentinel-2 data and don't know where to get it? [Click here for a walkthrough.](https://eae59453-626c-435a-aeb7-8b2466da9365.usrfiles.com/ugd/eae594_17089add367c437f9bd331ac98a815f6.pdf)

Please credit **Chris Cohrs** ([treepoet.com](https://www.treepoet.com)) if you use or share this work. 

All inquiries can be sent to cohrs.xyz@gmail.com. 
