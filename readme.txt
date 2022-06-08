DayZ 1.18 Namalsk Standard & Helicoter Trader For Use With Dr Jones Trader & RFFS Heliz

THESE ARE THE TEXT SNIPPETS FOR THOSE THAT WOULD LIKE TO MODIFY THEIR OWN TRADER CONFIG FILES,
PROBABLY BEACAUSE YOU HAVE OTHER MODDED ITEMS ALREADY INCLUDED, OR DAYZ HAS PROGRESSED PAST 1.18.

IF YOU'RE RUNNING A VANILLA 1.18 Namalsk SERVER JUST UPLOAD THE SUPPLIED TraderObjects.txt and TraderConfig.txt and TraderVehicleParts.txt files to the
Trader Config folder inside your Server Config / Settings / Profile folder.

MANY THANKS TO DR JONES, SUMRAK & RED FALCON

Trader is at 6316.00 / 9438.45, at the main Namalsk Airfield.

ADD THIS TO THE FIRST HALF OF TRADEROBJECTS.TXT AFTER THE (Tradermarker> 5 Entry:

<TraderMarker> 6
<TraderMarkerPosition>  6327.22998046875,                20.79560089111328,                9473.0302734375
<TraderMarkerSafezone> 20
<VehicleSpawn>			 6318.97998046875,               20.70159912109375,                9463.83984375
<VehicleSpawnOri>		-90.0,                0.0,                0.0

ADD THIS TO THE SECOND HALF OF TRADEROBJECTS.TXT AFTER THE <Object> SurvivorM_Peter	ENTRY:

<Object> 			SurvivorM_Boris					// heliz
<ObjectPosition>	   6327.22998046875,                20.79560089111328,                9473.0302734375
<ObjectOrientation>	  -159.99998474121095,                0.0,                0.0
<ObjectAttachment>	RFFSHeli_PilotHelmet
<ObjectAttachment>	RFFSHeli_PilotGloves
<ObjectAttachment>	RFFSHeli_PilotShirt
<ObjectAttachment>	RFFSHeli_PilotPants
<ObjectAttachment>	RFFSHeli_PilotVest
<ObjectAttachment>	MilitaryBoots_Black

<Object>			Land_RoadCone
 <ObjectPosition>	   6309.97509765625,                20.800397872924806,                9463.634765625
 <ObjectOrientation>	 0.0,                0.0,                0.0
 
 <Object>			Land_RoadCone
 <ObjectPosition>	 6320.95703125,                20.777193069458009,                9458.0068359375
 <ObjectOrientation>	 0.0,                0.0,                0.0
 
 <Object>			Land_RoadCone
 <ObjectPosition>	 6320.646484375,                20.7459659576416,                9468.736328125
 <ObjectOrientation>	 0.0,                0.0,                0.0

ADD THESE TO TraderVehicleParts.txt BELOW THE LAST M3S ENTRY:

<VehicleParts>RFFSHeli_Bo105m 
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7
        HeadlightH7

<VehicleParts>RFFSHeli_Bo105m_blackcamo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird 
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird_Camo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_LittleBird_Desert
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness    
        HeadlightH7

<VehicleParts>RFFSHeli_Ka26
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness 
        HeadlightH7   

<VehicleParts>RFFSHeli_Bell429
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Bell429_Police
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Bell429_Medic
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7

<VehicleParts>RFFSHeli_Mi2
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 
		
<VehicleParts>RFFSHeli_Mi2_Military
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 

<VehicleParts>RFFSHeli_Mi2_Hornet
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 	

<VehicleParts>RFFSHeli_Apache
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7  	

<VehicleParts>RFFSHeli_Apache_Winter
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7 	

<VehicleParts>RFFSHeli_Apache_Desert
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22_Red
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_R22_Black
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	

<VehicleParts>RFFSHeli_Blackhawk
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7	

<VehicleParts>RFFSHeli_Blackhawk_Cargo
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7

<VehicleParts>RFFSHeli_Blackhawk_Woodland
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7

<VehicleParts>RFFSHeli_CH53e
        RFFSHeli_aviation_battery
        RFFSHeli_igniter_plug
        RFFSHeli_hydraulic_hoses
        RFFSHeli_wiring_harness
        HeadlightH7	
        HeadlightH7
		

ADD THESE TO TraderConfig.txt, near the bottom, after the VehicleKeyLost entry:

<Trader> Heli Trader	
	 <Category> Helicopters
        RFFSHeli_Bo105m,            VNK,    50000,        -1
        RFFSHeli_Bo105m_blackcamo,            VNK,    50000,        -1
        RFFSHeli_LittleBird,        VNK,    50000,        -1
        RFFSHeli_LittleBird_Camo,    VNK,    50000,        -1
        RFFSHeli_LittleBird_Desert,    VNK,    50000,        -1
        RFFSHeli_Ka26,                VNK,    50000,        -1
        RFFSHeli_Bell429,                VNK,    50000,        -1
        RFFSHeli_Bell429_Police,                VNK,    50000,        -1
        RFFSHeli_Bell429_Medic,                VNK,    50000,        -1
        RFFSHeli_Mi2,                VNK,    50000,        -1
        RFFSHeli_Mi2_Military,                VNK,    50000,        -1
        RFFSHeli_Mi2_Hornet,                VNK,    50000,        -1
        RFFSHeli_Apache,                VNK,    50000,        -1
        RFFSHeli_Apache_Winter,                VNK,    50000,        -1
        RFFSHeli_Apache_Desert,                VNK,    50000,        -1
        RFFSHeli_R22,                VNK,    50000,        -1
        RFFSHeli_R22_Red,                VNK,    50000,        -1
        RFFSHeli_R22_Black,                VNK,    50000,        -1
		RFFSHeli_Blackhawk,                VVNK,    50000,        -1
        RFFSHeli_Blackhawk_Cargo,                VNK,    50000,        -1
        RFFSHeli_Blackhawk_Woodland,               VNK,    50000,        -1
        RFFSHeli_CH53e,                VNK,    50000,        -1

    <Category> Helicopter Parts
        RFFSHeli_hydraulic_fluid,    *,    200,        -1
        RFFSHeli_hydraulic_hoses,    *,    200,        -1
        RFFSHeli_wiring_harness,    *,    200,        -1
        RFFSHeli_igniter_plug,        *,    200,        -1
        RFFSHeli_aviation_battery,    *,    200,        -1
        RFFSHeli_aviation_toolbox,    *,    200,        -1
		RFFSHeli_flight_case,		*,		200,			-1
		RFFSHeli_flight_case_red,		*,		200,			-1
		RFFSHeli_flight_case_blue,		*,		200,			-1
		RFFSHeli_batterycharger,		*,		200,			-1
		
	<Category> Helicopter Gear
		RFFSHeli_PilotHelmet,		*,		200,			-1
		RFFSHeli_PilotGloves,		*,		50,			-1
		RFFSHeli_PilotShirt,		*,		100,			-1
		RFFSHeli_PilotPants,		*,		100,			-1
		RFFSHeli_PilotVest,		*,		50,			-1