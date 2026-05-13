# AIO DASHBOARD
Your all in one dashboard for all major simracing games supported by SIMHUB.

Supported simulators:
- Assetto Corsa
- Assetto Corsa Competizione
- Assetto Corsa Evo (partially, game in early phase)
- Assetto Corsa Rally (partially, game in early phase)
- Automibilista 
- Automobilista 2
- Rfactor 2
- Le Mans Ultimate (with NeoRed plugin)
- RaceRoom Racing Experience
- F1 Games (2010 to 2025)
- Forza Motorsport 7 & 8
- Dirt Rally 2
- Project Motor Racing
- Richard Burns Rally
- Live for speed (partially, some telemtry is missing in the game)
- IRacing
- BeamNG

Future supported simulators (Work in progress):
- WRC

# What this dash provide ?
3 screens:
- 1/ The first screen contain 4 widgets triggered by action A, B and C:
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03fb8bd5-f8da-4c33-a2ec-b9ee48d93d8b" />
 
  - Action A and B : 13 widgets :
    1) Lap delta + Time infos + Opponents gaps,
    2) Sectors infos,
    3) Relative gaps,
    4) Standings gaps,
    5) Map,
    6) Tires infos,
    7) Telemtry,
    8) On track and in class gaps,
    9) Pace,
    10) Pit screen,
    11) Tires analysis
    12) Radar,
    13) Damage infos 
  - Action C : Quick view for Fuel,PIT, Virtual Energy (LMU only) and Pace
  - Action D : Quick view for Damage and Radar
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/951341d6-5bf6-4e27-a330-f66ea83c80b2" />

- 2/ The second screen contains relative opponents lap times, class and laps times:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40ebfd81-ae74-472a-8076-eba784d290dc" />

- 3/ The third screen contains standings opponents lap times, class and laps times:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/69fb6863-2291-4eca-a587-0567122fff61" />

# The files:
- AIO Dashboard_Leds: The dashboard with an RPM leds
- AIO Dashboard_No_Leds: The dashboard without an RPM Leds

# To install:
- 1/ Please download the latest version of SIMHUB: https://www.simhubdash.com/download-2/
- 2/ Download the latest "AIO DASHBOARD" from the release section
- 3/ Install the dashbords by double clicking on the files
- 4/ Assign action and show next/previous screen buttons in SIMHUB: Go to Dash Studio -> Controls -> scroll down to "Default dashbord controls" and assign trigger action and show next/previous screen buttons to you liking

<img width="1920" height="1080" alt="001" src="https://github.com/user-attachments/assets/e25b6fc5-45a0-42a9-a15d-4542a8dbd2c9" />


# For LMU :

Since LMU update (1.2.0.1) the telemtry link between Simhub and LMU is broken. My LMU data are heavely based on NeoRed plugin.

Please update NeoRed plugin to the latest version and follow the installation instructions indicated by Haagel https://community.lemansultimate.com/index.php?threads/simhub-neored-plugins-and-dashboard-now-with-automatic-online-update-last-update-14-12-2025-v1-4-0-2.7638/

To install:
- 1/ Copy "LMU_SharedMemoryMapPlugin64.dll" to ..\Le Mans Ultimate\Plugins\ (to download : https://github.com/tembob64/LMU_SharedMemoryMapPlugin/releases )
- 2/ Copy "CustomPluginVariables.JSON" to ..\Le Mans Ultimate\UserData\player\ (to download : https://www.lmu-dashboards.com/index.html go to "Resources" -> "Plugin Collection" -> download "Custom Plugin Variables")
- 3/ Copy "NeoRed.lmuDataPlugin.dll" to the main SimHub folder ( should be C:\Program Files (x86)\SimHub\ ) and activate it in SimHub.
- 4/ Copy "LMU_SessionDataPlugin.dll" to the main SimHub folder ( should be C:\Program Files (x86)\SimHub\ ) and activate it in SimHub.


Please always check the links to have the latest and updated versions
This plugins are only required for LMU. No third pary plugins are needed for other games.

# For tires Slip/Lock (AC, ACC ,AC EVO, AC RALLY, LMU, RF2, RRRE, F1 2018-2025,Project Motor Racing, Dirt Rally 2, Gran Turismo 7, Project CARS 1 and 2, AMS2) :
Download and install the Viper4gh plugin for calculating wheels slip/lock ( place the *.dll file in main simhub directory and activate it in Simhub)
https://github.com/viper4gh/SimHub-Plugin-CalcLngWheelSlip/releases/

- 6/ Copy "Viper.PluginCalcLngWheelSlip.dll" to the main SimHub folder ( should be C:\Program Files (x86)\SimHub\ ) and activate it in SimHub.

# Great thanks goes to :
- Haagel ( https://www.overtake.gg/downloads/lmu-neosuperdash.77210/ ) for the NeoRed plugin for LMU
- Redadeg, Shaun86 and geims12 for the excellent plugins they made
- Viper4gh for the great Slip/Lock plugin
- nikolaiNr7 for the LMU-Electronic-Bridge plugin


Hope you like it, I will continue to try to improve it. Bug reports, comments, suggestions and even well-mannered criticism will be much appreciated.
