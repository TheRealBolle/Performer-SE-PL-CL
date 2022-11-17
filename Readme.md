# Micromac Performer SE/Plus/Classic Clone
  
This is a recreation of the MicroMac SE/Plus/Classic accelerator.  
The schematics have been reverse engineered and a new PCB was created based on the schematics.
  
![fully populated board](/Performer_populated.jpg)
  
The provided PCB files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use.  
  
  
  
# Notes on GALs and jumpers
  
The original GALs have been dumped. GAL16V8-15 as well as PALCE16V8-15 have been tested as suitable replacement.
Faster/slower chips as well as ATF16V8 of any speed haven't been tested so far.

U3, U4, U5 and U6 are mandatory. U7 is only needed for operation in Macintosh Plus and Classic.
Close SJ2 if U7 isn't installed. SJ2 HAS to be open when U7 is installed.

Close SJ1 to run the optional 68882 off the 16MHz accelerator clock.
Install an oscillator and open SJ1 to run the 68882 at any speed.
The original design used 25MHz which has been verified to work on the clone as well.

I have not found a socket that allows secure installation over the PLCC CPU in the Macintosh Classic.
Proper operation has been tested in the Macintosh Plus and SE but so far not on the Classic.
  
# Board Files
  
The provided gerber files have been generated using the JLCPCB EAGLE cam job files.  
