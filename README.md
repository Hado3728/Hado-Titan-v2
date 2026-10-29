<img width="1487" height="787" alt="ASSEMBLED" src="https://github.com/user-attachments/assets/5ca4b024-aa15-43cf-a5a2-d0f017a98dc5" />
# Hado Titan V2

###### An 8 kg invertible drum spinner. The steel drum is belt driven and the chassis is laser-cut, bent sheet aluminium.




|||
|-|-|
|Weight|7.78 kg of 8 kg (218 g spare, wiring included)|
|Size|386 × 268 × 100 mm|
|Weapon|Spinning drum|
|Weapon numbers|7,640 rpm, 539 J, 31 m/s at the tips, 0.9 s spin-up|
|Drive|2 × PG36M555 gearmotors → 18:27 laser-cut gears → 100 mm wheels. 1.9 m/s, \~50 N push|
|Battery|6S 2500 mAh 35C. A hard 5-minute fight.|
|Cost|₹51,757 ($548) for the robot, ₹54,800 ($580) including a charger|



## How it works

**Weapon.** A Flipsky 5065 270KV drives the drum through a 280-5M-15 belt (30T → 20T, 1.5:1 overdrive). The ESC is a ZeroDrag AM32, current-limited to 50 A. The drum's 20T pulley teeth are cut into the drum itself. The motor pulley is a stack of laser-cut plates: 5 toothed plates, 2 flanges and a hub. The drum runs on 6203 bearings on a hollow EN24 shaft. Both shaft ends are tapped M12 and bolted through two stacked 10 mm plates on each side.

**Drive.** Each wheel has its own axle on two bearings, and the gearmotor drives it through a flat 18:27 involute gear pair. Hits and drops go through the bearings into the frame, not into the gearbox. The motors are staggered, one in front of its axle and one behind, so they fit across the chassis.

**Invertible.** The wheels stick out 17 mm past the floor and the lid. The forks are double-ended. One transmitter switch reverses throttle and weapon when the bot is upside down; steering doesn't change.

**Chassis.**

* 3 mm 5052 U-channel (floor + side walls), brake-bent, with a rolled R50 rear wall tabbed into the floor.
* 2.5 mm 6061 lid on M4 rivnuts.
* Everything else is flat laser-cut plate, gears included.
* The electronics sit in TPU cradles lined with EVA foam, screwed to the floor.

## Numbers





|||
|-|-|
|Centre of mass|51 mm ahead of the axle, centred side to side and top to bottom|
|Weight on wheels|73% (the fork tips carry the rest, so they stay on the floor)|
|Drum torque|2.4 N·m at the 50 A limit. Belt pull 153 N|
|Drum momentum|1.35 N·m·s. One wheel starts to lift above \~0.8 turns/s with the drum at full speed|
|Push|41 N continuous, \~100 N burst from the motors, capped at \~50 N by traction. Beats an 8 kg bot sitting with locked wheels (\~47 N)|
|Re-spins|Each spin-up costs 0.2 Wh. About 27 are left after a hard 5-minute fight|
|Peak current|\~76 A = 30C (pack is rated 35C)|



## BOM





|Section|₹|
|-|-:|
|Electronics|29,817|
|Machining (CNC drum, heat treat, lathe parts)|12,241|
|Bought mechanical (bearings, belts, tyres, foam)|2,530|
|Wiring|2,417|
|Fasteners|1,771|
|Metal, laser cut + bent (₹375/kg)|1,621|
|3D printing (TPU)|1,360|
|Charger (only if needed)|3,043|
|**Total**|**54,800 ($580)**|

## 

## Weight





|Group|g|
|-|-:|
|Drum, shaft, bearings, spacers|2326|
|Drive (gearmotors, gears, bulkheads, saddles)|1062|
|Tub, rear wall, splices|903|
|Wheels, axles, bearings, doublers|616|
|Weapon motor, pulley, belt, mount|613|
|Weapon uprights|602|
|Electronics|536|
|Lid|401|
|Fasteners|265|
|Forks|164|
|TPU cradles + foam|154|
|Wiring|140|
|**Total**|**7782**|



