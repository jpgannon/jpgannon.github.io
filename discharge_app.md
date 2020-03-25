## An app for exploring discharge in a small mountain catchment
[The Gribble Gap Discharge app](http://198.82.212.36/GribbleGap_Discharge/) is a R shiny web application designed to give students a way to explore the discharge record of a headwater stream in a variety of ways. 

Eventually this page will host some classroom activities, but for now, there is simply a list of topics that can be explored with the app.

## Concepts to explore
#### Discharge variations over a water year 
These are more apparent using the logged y axis

#### Storm dynamics
You can highlight days with certain precipitation amounts, so you can compare responses in different seasons and or wetness conditions. Use the "add horizontal line" to compare storm magnitudes easily.

#### Water balance concepts 
Total discharge and precip in mm is included for the time period shown in the plots

#### Water temperature dynamics 
Click the checkbox to add the water temperature record to the plots

#### Baseflow dynamics
You can show baseflow, calculated using the [EcoHydRology package](https://cran.r-project.org/web/packages/EcoHydRology/index.html) in the plots. You can also change the filter parameter for the baseflow filter function.

#### Flow Duration/Non-exceedance curves 
There is a probability of non-exceedance curve for the total flow and calculated baseflow. A second line appears if you zoom in to a specfic time-frame, which shows the curve for just that time frame. This can help illustrate what these curves show.

#### Note: 
Plots can be copied via right click for pasting into documents.


### Contact
If you use this app for a class or otherwise, I would greatly appreciate it if you let me know! Suggestions for features and/or information about bugs are also very welcome and encouraged.

You can contact me via direct message on twitter (@jp_gannon) or by email at jpgannon [at] vt.edu

### Data
The data used in the app are hosted on CUAHSI Hydroshare and can be accessed [here](https://www.hydroshare.org/resource/156bed7f9b984677ad617fd071a99a33/)
