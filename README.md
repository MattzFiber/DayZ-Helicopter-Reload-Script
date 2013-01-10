DayZ-Rearm-Script
================

A DayZ Rearm by MattzFiber
If your gonna edit it, please let me know.


Instructions
================
Mod your mission.sqm and add it with the lines of code provided (Add it in)

Please make sure you place this in the right place!

After this in the mission file:
	randomSeed=2920725;
	class Intel
	{
		startWeather=0.25;
		forecastWeather=0.25;
		year=2008;
		month=10;
		day=11;
		hour=9;
		minute=20;
	};
	
is where you place "class Vehicles"
straight after that is where you place "class Sensors"

Put scriptsMZ in that EXACT location, or it will not work..

For BE Script Kicks:

Find this:
5 setVehicleAmmo !"\"setVehicleAmmo\","
At the end of that line add 
!"scriptsMZ\MZ_helo.sqf"
Just like that

Find this:
5 setFuel blahblah
At the end of that line add 
!"scriptsMZ\MZ_helo.sqf"
Just like that

Find this:
5 addMagazine
At the end of that line add 
!"scriptsMZ\MZ_helo.sqf"
Just like that


Comments/Feedback/Support here:
http://opendayz.net/index.php?threads/chopper-ammo-refuel.7070/