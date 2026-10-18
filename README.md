
     ██████                 ██            ███████                              ██   
    ░█░░░░██               ░██  ██   ██  ░██░░░░██                            ░██   
    ░█   ░██   ██████      ░██ ░░██ ██   ░██   ░██  ██████   ███████   █████  ░██   
    ░██████   ██░░░░██  ██████  ░░███    ░███████  ░░░░░░██ ░░██░░░██ ██░░░██ ░██   
    ░█░░░░ ██░██   ░██ ██░░░██   ░██     ░██░░░░    ███████  ░██  ░██░███████ ░██   
    ░█    ░██░██   ░██░██  ░██   ██      ░██       ██░░░░██  ░██  ░██░██░░░░  ░██   
    ░███████ ░░██████ ░░██████  ██       ░██      ░░████████ ███  ░██░░██████ ███   
    ░░░░░░░   ░░░░░░   ░░░░░░  ░░        ░░        ░░░░░░░░ ░░░   ░░  ░░░░░░ ░░░    
                                                                                   
          ██            ████                        ’Body-Panel-Info.FCMacro’      
         ░██           ░██░                                                        
         ░██ ███████  ██████  ██████                 Faehnchen, 18 Okt. 2026       
         ░██░░██░░░██░░░██░  ██░░░░██                                              
         ░██ ░██  ░██  ░██  ░██   ░██                FreeCAD version 1.1.4         
         ░██ ░██  ░██  ░██  ░██   ░██                                              
         ░██ ███  ░██  ░██  ░░██████                 License: GPL 3.0 (see end)    
         ░░ ░░░   ░░   ░░    ░░░░░░                                                


# About:

This Macro adds some useful property information to your PartDesign-Body Data-
properties panel:

- Assigned Material
- Material Density
- Volume in mm³
- Mass in g and lb

You can view all these values in one glance at the panel. Toggle the display of 
units on and off with a checkbox.

Units stay consistent regardless how big the model grows (no unit shifting)

# Usage:

Put this script into the macro folder specific to your OS and installation method
(investigate place: *Edit > Preferences > Python > Macro*)

Select and activate the PartDesign Body container you want to add the property
infos. Run the Macro.

**Note:** The Macro only runs if there is alread a volume in the body container!

After all properties are ceated, manually set the ones with leading *’_’* to
’Hidden’ (*right-click > Status*) and the other ones to *’Read Only’*.

The values most often trail one feature of the model behind. For displaying the
definitive values, recompute the whole model or check/uncheck the unitsdisplay
switch.

