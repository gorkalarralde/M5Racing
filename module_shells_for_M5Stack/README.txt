                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:2834201
module shells for M5Stack by n602 is licensed under the Creative Commons - Attribution - Share Alike license.
http://creativecommons.org/licenses/by-sa/3.0/

# Summary

module shells for M5Stack

M5Stack ; http://m5stack.com/
The source of information on hardware is the following site.
https://github.com/m5stack/M5-hardware

For the dimensional information necessary for this thing, refer to the instructions enclosed with the m5stack product.

-CAD DATA.
stack047_.stp ; step format
stack047_.123dx ; Autodesk123D file

-STL file.
stack047_prt0.stl ; PROTO module shell
stack047_prtbt1.stl ; PROTO-Bottom module shell (H 6.6mm).
stack047_prtbt2.stl ; PROTO-Bottom module shell (H 13.2mm). 
stack047_prtbt3.stl ; PROTO-Bottom module shell (H 13.2mm).
stack047_btm.stl ; BOTTOM module shell, without magnets.
stack047_btm2.stl ; BOTTOM module shell, Battery-UpGradable, without magnets.

-It seems that "503048"(850mAh) is built in the "Battery function module", M5Stack products.
-Deviations from proper usage of LiPo batteries are a big risk for you.
-Please select LiPo battery by judgment based on correct knowledge.

----------

*** update 5/20/2018
AMP&SPK module [experimental]

-CAD DATA.
stack047_spk-vol_03.stp ; step format
stack047_spk-vol_.123dx ; Autodesk123D file
-STL file.
stack047_spk-vol_03.stl ; module shell

This is an experimental attempt to add volume adjustment function to M5 Stack.
This is a SPK& module  in order to avoid adding as much as possible inside M5 Stack Core.
Please refer to the schematic of M5 Stack core and find and confirm how to disable AMP.(NS4150) inside M5 Stack core.
The parts, circuits, and circuit constants shown in the photo may not necessarily be the ideal correctness.
Even if M5 Stack and peripheral devices are damaged by this thing, I can not take responsibility for it.
If you try this, please check the selection of parts and circuits at your own risk.



# Print Settings

Printer Brand: FlashForge
Printer: Creator Pro
Rafts: No
Supports: Yes
Resolution: 0.2mm
Infill: 75% or more

Notes: 
Slicer; Simplify3D
Filament; PLA-PolyPlus
Temp.; 210C
Speed; 55mm/s
TopSolidLayers;3 / Bottm;3 / Shell;2