# Micromac Performer SE/Plus/Classic Clone
  
This is a recreation of the MicroMac SE/Plus/Classic accelerator.  
The schematics have been reverse engineered and a new PCB was created based on the schematics.
  
![fully populated board](/Performer_populated.jpg)
  
The provided PCB files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use.  
  
  
  
# Reverse engineered GALs
  
The original GALs have been dumped. GAL16V8-15 as well as PALCE16V8-15 have been tested as suitable replacement.
Faster/slower chips as well as ATF16V8 of any speed haven't been tested so far.

U3, U4, U5 and U6 are mandatory. U7 is only needed for operation in Macintosh Plus and Classic.
Close SJ2 if U7 isn't installed. SJ2 HAS to be open when U7 is installed.
  
  
# Board Files
  
The provided gerber files have been generated using the JLCPCB EAGLE cam job files.  
