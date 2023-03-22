# MinX
Lightweight toolchanging for Voron V2.4 and Trident.

**Note: This is not being actively developed! I may revisit this again in the future**

# Motivation
After using the stealthburner toolhead, I found that it did not meet my needs. The stealthburner toolhead is designed for many different hot end and extruder configurations, where I only use one (Orbiter + rapido).

Therefore, it should be theoretically possible to build a much simpler toolhead assembly that is a lot lighter. I am thinking somewhere along the lines of the VZbot toolhead, but applied to the Voron ecosystem.

# Planned Features
- Integrated Klicky probe mount
- ERCF compatibility
- Rapido UHF hotend for release, other hotends to come after release if there is demand
- Orbiter V2.0 Extruder
- CPAP part cooler


# Development roadmap
1) [IN PROGRESS] Develop proof of concept mount. The aim here is to mount the extruder, hot end, klicky and hot end fan. Concept CAD appears to work. <br />


[Video of mating mechanism](https://youtu.be/YaVQcDJk54c)

Preliminary Design CAD:

![image](https://user-images.githubusercontent.com/12782053/183279377-0118a218-ef77-4142-b4d9-53120669a527.png)
![image](https://user-images.githubusercontent.com/12782053/183279398-2e3ba608-d6ee-4381-8b6c-7e4dd5762536.png)
![image](https://user-images.githubusercontent.com/12782053/183279407-1ac8da6f-45cc-429a-bdc2-b17e870ff0db.png)
![image](https://user-images.githubusercontent.com/12782053/183279418-59e6a3bd-abdd-408a-92bd-c51c0c52500b.png)
![image](https://user-images.githubusercontent.com/12782053/183279426-dcafe0ba-4bee-44b4-8050-5d2f6f574953.png)
![image](https://user-images.githubusercontent.com/12782053/183279430-b140cca3-ffac-4108-bebc-d565dee58619.png)


2)  [IN PROGRESS] Develop part cooling fan shroud.
3)  Integrate into assembly and release.


There are no release dates for anything - they will be completed when they are ready.

# Installation
The following modifications are required for this toolhead:
1) Klicky mod
2) Removal of cable chains - recommend using CANBUS toolhead PCB
3) CPAP fan 
