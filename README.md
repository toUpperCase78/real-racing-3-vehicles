# real-racing-3-vehicles
**Dataset for All Vehicles in Real Racing 3**

![Real Racing 3](real_racing_3_image(9).png)

I've been playing this mobile racing game, **Real Racing 3** (developed by Firemonkey and published by Electronic Arts) for several years. Although the game is 9 years old, it still gets updates several times each year, which includes new vehicles, tracks, career & motorsport series, special events & exclusive series. Up to now, it contains over 350 vehicles available for purchase and drive.

Meanwhile, as a Data Science enthusiast, here I've created these datasets that list all the vehicles appeared in the game; also including those that no longer available for purchase. 

I started this repository project from **game version 8.0**. Here, you can find vehicle datasets for all individual versions and data analyses await for valuable insights in the upcoming days!

All the values in these datasets are obtained from the game's [wiki website](https://rr3.fandom.com/wiki/Main_Page).

_From time to time, I will keep the dataset up-to-date once new versions have been released, along with minor fixes whenever necessary..._

## Version Info

**Dataset Version:** 2.4.18

**Last Updated:** 30th July 2022

**Vehicle Roster Dependency:** Game Version 10.5 - Valhalla Update

## Features

**The latest dataset contains these features below for each vehicle:**
* `Manufacturer` : The manufacturer name (or motorsport discipline)
* `Model` : The model name of the manufacturer
* `PR` : Base Performance Rating value (i.e. no upgrades exist)
* `Top Speed` : Base top speed value (in kph)
* `Acceleration` : Base acceleration value (in seconds)
* `Braking` : Base braking value (in meters)
* `Grip` : Base cornering grip value (in g)
* `Class` : Indicates the vehicle class (`P`, `S` or `R`)
* `Type` : Indicates the vehicle type w.r.t. engine placement and traction (e.g. `FR`, `M4`, `RR`) 
* `Series` : Describes the number of eligible career series the vehicle can be driven
* `Price` : The value for purchasing the vehicle with the related currrency type (`R$`, `Gold` or `M$`)
* `Service Time` : Required total servicing time (in minutes)
* `Service Cost` : Required servicing cost (in R$)
* `Availability` : Indicates whether or not the vehicle is available for purchase in the game
* `Exclusive Events` : Indicates whether or not the vehicle has its own exclusive events when fully upgraded
* `In Main Career`: Indicates whether or not the vehicle is involved in main career series

## My Analyses

1st Part of My Analysis is [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_analysis1_rev3.ipynb), containing several data analyses **(for game version 10.1)**.

2st Part of My Analysis is [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_analysis2_rev2.ipynb), containing more data analyses **(for game version 10.1)**.

3rd Part of My Analysis is [here](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_analysis3_rev2.ipynb), focusing on data visualization **(for game version 10.1)**.

**All these studies have been carried out in IPython Shell.**

## Notes

**Note 1:** It is bizarre that values that contained `$` appeared problematically, causing some missing rows and unusual sizing in the output due to rendering by GitHub when uploaded here. For this reason, texts containing `$` sign have been changed within the analyses.

**Note 2:** Due to new game versions and minor changes to datasets such as insertion of new vehicles and/or fixing erroneous values, experiments that were presented in outcomes might not be 100% accurate or out-of-date. That's why they will be fixed some time later to reflect those changes.

## AS ALWAYS, KEEP RACING!
