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
  
  
  
# BOM
  

Part           Value          Package       Library       Position (mil)        Orientation

C1             22uF   	      C/6032-28W    rcl           (3400 3300)           R0
C2             22uF           C/6032-28W    rcl           (2350 1300)           R270
C3             22uF           C/6032-28W    rcl           (610 3300)            R90
C4             100nF          C1206         rcl           (2100 2930)           R90
C5             100nF          C1206         rcl           (275 1500)            R0
C6             100nF          C1206         rcl           (-400 1250)           R0
C7             100nF          C1206         rcl           (1250 450)            R270
C8             100nF          C1206         rcl           (450 750)             R0
C9             100nF          C1206         rcl           (400 3140)            R0
C10            100nF          C1206         rcl           (4080 2580)           R0
C11            100nF          C1206         rcl           (100 770)             R270
QG1            25MHz          DIL14S        crystal       (-150 3250)           R180
R1             4k7            R1206         rcl           (-400 1450)           R180
R2             4k7            R1206         rcl           (-400 1550)           R180
R3             4k7            R1206         rcl           (300 3300)            R90
R4             4k7            R1206         rcl           (200 770)             R90
R5             4k7            R1206         rcl           (400 3300)            R90
R6             4k7            R1206         rcl           (1900 1270)           R270
R7             4k7            R1206         rcl           (2100 1270)           R270
R8             4k7            R1206         rcl           (2200 1270)           R270
R9             4k7            R1206         rcl           (1350 450)            R90
R10            4k7            R1206         rcl           (-400 1350)           R180
R11            4k7            R1206         rcl           (-400 1050)           R180
R12            4k7            R1206         rcl           (500 3300)            R90
R13            4k7            R1206         rcl           (100 1650)            R180
R14            4k7            R1206         rcl           (2000 1270)           R270
R15            4k7            R1206         rcl           (-400 1150)           R180
R16            4k7            R1206         rcl           (1450 450)            R90
R17            4k7            R1206         rcl           (-400 1650)           R180
R18            4k7            R1206         rcl           (-100 1650)           R0
U1             MC68030RC16    MPGA128       micro-mc68000 (1350 2450)           R90
U2             68882          PLCC68-S      micro-mc68000 (0 2350)              R0
U3             GAL16V8-15     PLCC20        GAL           (900 475)             R270
U4             GAL16V8-15     PLCC20        GAL           (400 475)             R90
U5             GAL16V8-15     PLCC20        GAL           (-250 700)            R180
U6             GAL16V8-15     PLCC20        GAL           (-75 1300)            R180
U7             GAL16V8-15     PLCC20        GAL           (3775 2375)           R270
