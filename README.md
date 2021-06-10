# real-racing-3-vehicles
**Dataset for All Vehicles in Real Racing 3**

![Real Racing 3](https://i.ibb.co/PtnQjDc/real-racing-3-logo-1.png)

I've been playing this mobile racing game, **Real Racing 3**, developed by Firemonkey and published by Electronic Arts, for several years. Although the game is 8 years old, it still gets updates several times each year, which includes vehicles, tracks, career series, special events, exclusive series, motorsport series. Up to now, it contains over 300 vehicles available for purchase and drive.

Meanwhile, as a Data Science enthusiast, here, I've generated these datasets that list all the vehicles appeared in the game; also including discontinued ones, starting from game version 8.0. Thus, these datasets are ready for analyses and await for valuable insights!

All the values in these datasets are obtained from the game's [wiki website](https://rr3.fandom.com/wiki/Main_Page).

From time to time, I will keep the dataset up-to-date once new vehicles have been released, along with minor fixes...

## Version Info

**Dataset Version:** 2.4.0

**Last Updated:** 10th June 2021

**Vehicle Roster Dependence:** Game Version 9.4 - NASCAR 2021 Update

## Features

This dataset contains these features below for each vehicle (according to the last dataset version):
* `Manufacturer` : The manufacturer name
* `Model` : The model name of the manufacturer
* `PR` : Base Performance Rating value (i.e. no upgrades applied)
* `Top Speed` : Base top speed value in kph
* `Acceleration` : Base acceleration value in seconds
* `Braking` : Base braking value in meters
* `Grip` : Base cornering grip value in g
* `Class` : Indicates the vehicle class (could be `P`, `S` or `R`)
* `Type` : Indicates the vehicle type w.r.t. engine placement and traction (e.g. `FR`, `M4`, `RR`) 
* `Series` : Describes the number of eligible career series the vehicle can be driven
* `Price` : The value for purchasing the vehicle with currrency type (could be R$, Gold or M$)
* `Service Time` : Required total servicing time in minutes
* `Service Cost` : Required servicing cost in R$
* `Availability` : Indicates whether or not the vehicle is available for purchase in the game
* `Exclusive Events` : Indicates whether or not the vehicle has its own exclusive events when fully upgraded
* `In Main Career`: Indicates whether or not the vehicle is involved in main career series

## My Outcomes

1st part of my outcomes is available [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_outcome1_rev2.ipynb), containing several data analyses **(revised for game version 9.0)**.

2st part of my outcomes is available [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_outcome2_rev1.ipynb), containing more data analyses **(revised for game version 9.0)**.

3rd part of my outcomes is available [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_outcome3_rev1.ipynb), focusing on data visualization **(revised for game version 9.0)**.

**All these studies have been carried out in IPython Shell.**

## Notes

**Note 1:** It is bizarre that values that contained `$` appeared problematically, causing some missing rows and unusual sizing in the output due to rendering by GitHub when uploaded here. For this reason, texts containing `$` sign have been changed.

**Note 2:** Due to new game versions and minor changes to datasets such as insertion of new vehicles and/or fixing erroneous values, experiments that were presented in outcomes might not be 100% accurate or out-of-date. That's why they will be updated some time later to reflect those changes.

**Note 3:** Sometimes, GitHub is stubborn to load the IPython files when it is taking too long. Just click on **Reload** if it is ended with **something going wrong**.
