# Ender3_switchwire_fixes
 Some fixes to popular ender 3 switchwire conversions

 [Triano](https://github.com/walttriano/Ender_3Pro_Switchwire) and [DaRk_dOg](https://github.com/boubounokefalos/Ender_SW) have produced an Ender 3 switchwire conversion mod. I'vew found a few issues during construcion and I thought I'd share my fixes. I reccomend starting with rev2 of DaRk_dOg's mod.

 ## WARNING
 **Before attempting an Ender 3 to switchwire mod, check your frame is not bent.** This will save you a lot of time later when things don't line up.

## Changes

- ### 2022-12-12
  - [Improved XZ Blocks](XZ-blocks/readme.md)
    - Added XZ blocks based on [Yenda's robust belt paths](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/yenda/vsw_more_robust_belt_paths) 

  - [Y Cable Chain Mount](Y-chain-mount/readme.md)
    - Added revised DaRk_dOg y cable chain mount that moves the mounting screw above the chain so mount can be removed with the chain in place. [Y-chain-mount](Y-chain-mount/Screenshot%202022-12-11%20195415.png)

- ### 2022-11-28
  -[mount for larger Y motors](Y-motor/readme.md)
    - Updated Y motor mount for better clearances. 
  
- ### 2022-07-10
  - [Y_limit_switch](Y_limit_switch)
    - Quick and dirty hack on Y limit switch for more travel into -Y so the very front of the bed can be probed.

- ### 2022-04-25
  - Reworked Y motor mod for 48mm steppers to work with pro and V2 with a spacer
  - Added small bed knobs with 5 minute and 1 minute indents, edges of the large indents are 1 minute from the centre. Minutes here refer to clockface and not minutes of a degree.
- ### 2022-02-16
  - Added modified rear deck for Y motor mod. Compatible with V2 and Pro Y rail.
- ### 2022-02-14
  - please note these mods are now deprecated
  - ~~Changed XZ blocks for [clearance](XZ-blocks/clearance.png), they don't sit flat to the extrusion~~
  - ~~Added a T-slot version with slightly differenc clearances~~
  - ~~Added my Y-idler fix to [very weak part](Y-idler/weak-slider.png)~~
- ### 2022-02-13
  - Depricated, see yenda based XZ blocks
  - ~~2 Fixed XZ blocks where the spacer isn't long enough~~
  - ~~added some 5mm ABS washers in case M5x35 BHCS aren't available~~
  - Added [Y motor mount](Y-motor/Y-Axis_2022-Feb-12_03-43-32AM-000_CustomizedView12767374662.jpg) for V2 with the pulley reversed, so a 48mm stepper like an E3D High Torque can be used, or the voron spec LDOs of simialr specification and size. 

## Todo
- ~~Upload rear motor mount~~
- ~~Upload Y tensioner quickfix~~
- ~~X-Z motor mount screw length changes (using washer works)~~
- Upper Block screw length changes (using washers works)
- ~~Add 10mm spacer to Y-axis, remove extension~~
- ~~Adapt printable deck for Y-motor~~

Find more [switchwire conversion mods](https://github.com/SW-Conversion/mod-regisistry)