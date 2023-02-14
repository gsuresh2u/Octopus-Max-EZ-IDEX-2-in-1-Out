# Octopus-Max-EZ-IDEX-2 in 1 Out
 Octopus-Max-EZ-IDEX-2 in 1 Out

 I am new to Klipper, Please help me o configure for 2 in 1 out hottends in IDEX Mode

 Board Respository : https://github.com/bigtreetech/Octopus-Max-EZ
 
 Board url : https://biqu.equipment/collections/control-board/products/bigtreetech-btt-octopusmax-ez-for-3d-printer

 Reference for 4 extruders in IDEX : https://github.com/DrumClock/my_config

 Hi, i want to configure Klipper for IDEX mode wih 2 in 1 out Hotend

 My drivers are X1 = EZ5160,
                X2 = EZ5160,
                Y1 = EZ5160,
                Y2 = EZ5160,
                Z1 = EZ5160,
                Z2 = EZ5160

 and exttruders drivers are E0 = EZ2209,
                            E1 = EZ2209,
                            E2 = EZ2209,
                            E3 = EZ2209

 Bed size 550 (X) x 550 (Y) x 500 (Z)

 My endstops are X-Minimum = NPN Probe with Normally Open (NO)
 
                 X-Maximum = NPN Probe with Normally Open (NO)
				 
                 Y-Minimum = NPN Probe with Normally Closed (NC)
				 
                 Z-Minimum = CR Ttouch

I am using all axis as Lead Screws, no Blet drive
One Rotaion travel distance = 12 mm (all axis), steps per unitt in Marlin = 533.33 (for 32 microsteps)
All my extruders are Dual gear Exruders Steps per unit in Marlin = 322.12 (for 32 microsteps)



