# Real Racing 3 Vehicles
**Datasets & Analyses for All Vehicles in Real Racing 3**

![Real Racing 3](Images/real_racing_3_image(26).png)

Hello folks! I've been playing this mobile racing game, **Real Racing 3** (developed by Firemonkey and published by Electronic Arts) for several years. Although the game is 11 years old, it still gets updates several times each year, which includes new vehicles, tracks, career & motorsport series, special events & exclusive series. Up to now, it contains over 400 vehicles available for purchase and drive.

Meanwhile, as a Data Science enthusiast, here I've created these datasets that list all the vehicles appeared in the game for each version; also including those that no longer available for purchase. 

I started this repository project from **game version 8.0**. Here, you can find vehicle datasets for all individual versions and data analyses await for valuable insights in the upcoming days!

All the values in these datasets are obtained from the game's [wiki website](https://rr3.fandom.com/wiki/Main_Page).

_From time to time, I will keep the dataset up-to-date once new versions have been released, along with minor fixes whenever necessary..._

## Version Info

**Latest Dataset Version:** 3.3.2

**Last Updated:** 20th October 2024

**Vehicle Roster Dependency:** Game Version 12.7 - Koenigsegg CC850 Update

## Dataset Features

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
* `Is Available` : Indicates whether or not the vehicle is available for purchase in the game
* `Has Exclusive Events` : Indicates whether or not the vehicle has its own exclusive events when fully upgraded
* `In Main Career`: Indicates whether or not the vehicle is involved in main career series
* `In Season 1` : Indicates whether or not the vehicle is involved in special events, limited-time series or bonus career series in all rounds of Season 1
* `In Season 2` : Indicates whether or not the vehicle is involved in special events, limited-time series or bonus career series in all rounds of Season 2
* `In Season 3` : Indicates whether or not the vehicle is involved in special events, limited-time series or bonus career series in all rounds of Season 3

## Additional Dataset

In the meantime, an additional dataset can be seen in the repo, containing all the series across all different disciplines and tiers from **Motorsports** and **Road Collection** (including special career series and exclusive series) for the latest version of Real Racing 3. 

Each row represents the main tab, name of the group, name of the series and individual vehicle with the manufacturer-model name belonging to that series. So, please make sure taking a look at the new dataset to observe the eligibility of any vehicle you enjoy!

## My Data Analyses

Data analyses are available in separate parts. You can click on the links in the table and inspect them all.

**All these analyses have been prepared in IPython Shell and are based on game version 12.6.**

| Parts | Features |
| ----- | -------- |
| [Part 1](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_Analysis1_Rev5.ipynb) | Basic & Intermediate Data Analyses |
| [Part 2](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_Analysis2_Rev4.ipynb) | Advanced Data Analyses |
| [Part 3](https://github.com/toUpperCase78/real-racing-3-vehicles/blob/master/RR3_Analysis3_Rev4.ipynb) | Several Data Visualizations |

## Notes

**Note 1:** It is bizarre that values that contained `$` appeared problematically, causing some missing rows and unusual sizing in the output due to rendering by GitHub when uploaded here. For this reason, texts containing `$` sign have been changed within the analyses.

**Note 2:** Due to new game versions and minor changes to datasets such as insertion of new vehicles and/or fixing erroneous values, experiments that were presented in outcomes might not be 100% accurate or out-of-date. That's why they will be fixed some time later to reflect those changes.

## My Vehicle Wishlist

By the way, I'd like to see these vehicles to be purchasable and driveable in the future updates of Real Racing 3! Here's my wishlist:

- [ ] Abarth 124 Spider
- [ ] Abarth 500
- [ ] Alfa Romeo Giulia GTAm
- [ ] Alpine A110 (2017)
- [ ] Aston Martin DB5
- [ ] Aston Martin DB12
- [ ] Aston Martin Superleggera DBS
- [ ] Aston Martin Vantage (2024)
- [ ] Aston Martin Zagato
- [ ] Audi Quattro S1 Rally
- [X] ~~Audi R8 (New Gen.)~~
- [ ] BMW i8
- [X] ~~BMW M3 GTR~~
- [X] ~~BMW M4 Coupe~~
- [ ] Bugatti Centodieci
- [ ] Bugatti Tourbillon
- [ ] Ferrari 12Cilindri
- [X] ~~Ferrari 296 GTB~~
- [X] ~~Ferrari 499P~~
- [ ] Ferrari 812 GTS
- [ ] Ferrari F2004
- [ ] Ferrari F80
- [X] ~~Ferrari Monza SP1~~
- [ ] Ferrari Roma
- [ ] Ford Focus RS (2017)
- [X] ~~Ferrari SF90 Stradale~~
- [X] ~~Formula 1 2022 Season~~
- [X] ~~Formula 1 2023 Season~~
- [X] ~~Formula 1 2024 Season~~
- [ ] Formula 1 2024 Season Safety Cars (Mercedes-AMG & Aston Martin)
- [ ] Honda Civic Type-R (Latest Gen)
- [X] ~~Koenigsegg CC850~~
- [X] ~~Koenigsegg Gemera~~
- [X] ~~Koenigsegg Jesko~~
- [ ] Lamborghini Egoista
- [ ] Lamborghini Revuelto
- [ ] Lamborghini Temerario
- [ ] Lancia Delta HT Integrale
- [ ] Lotus Elise
- [ ] Lotus Evora
- [ ] Maserati MC12
- [ ] Maserati MC20
- [X] ~~Mazda MX-5 (ND)~~
- [ ] Mazda RX-8
- [X] ~~McLaren Artura~~
- [ ] McLaren MP4-13
- [ ] McLaren Solus GT
- [ ] McLaren W1
- [ ] Mercedes-AMG ONE
- [ ] Mini John Cooper Works
- [ ] Mitsubishi Lancer Evolution IX
- [ ] Mitsubishi Lancer Evolution X
- [X] ~~Nissan Z~~
- [ ] Peugeot 9X8
- [X] ~~Porsche 911 Carrera (992)~~
- [ ] Porsche 911 RSR (2024)
- [ ] Renault R26
- [X] ~~Rimac Nevera~~
- [ ] Saleen S7
- [ ] Subaru BRZ
- [ ] Subaru Impreza WRX STI (2nd-5th Gen.)
- [ ] Toyota Supra (Latest Gen)
- [ ] W Motors Lykan Hypersport

## AS ALWAYS, KEEP RACING!
