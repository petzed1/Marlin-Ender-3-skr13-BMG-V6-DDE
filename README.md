I have Creality Ender 3 Pro with these upgrades:
* skr v1.3 with TMC2209 drivers in UART mode. 
* Direct drive extruder with BMG extruder and stepper NEMA17 on extruder. Printed all kit from Trianglelab on Aliexpress.com 24V Kit
* BLTouch probe
* Hotend termistor ATC Semitec 104GT-2/104NT-4-R025H42G
* Dual Z with belt - comming soon  

Marlin-bugfix 2.0.7  setup enabled:
* all stepper with spreadCycle
* Linunear advance with K 0.05 and EXPERIMENTAL_SCURVE
* bltouch NOZZLE_TO_PROBE_OFFSET { 38, -3, -1 }, 
* GRID_MAX_POINTS_X 6 total 36 points  speed up init AUTO_BED_LEVELING_BILINEAR
* AUTO_BED_LEVELING_UBL comming soon
* Custom Menu
* TMC_debug
* Fix the skr1.3 speaker issue
* more changes and tools
