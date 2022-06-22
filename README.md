# SFS-KSP-Showcase
A varied collection of vehicles for the updated version of KSP

![](https://github.com/bobbybudnick/SFS-KSP-Showcase/blob/main/20220621230328_1.jpg)

Mods
-----
KSPIE  
Mechjeb  
Click Through Blocker  
Toolbarcontrol  
Vertical Velocity Controller Redux

Alcubierre drive notes
-----
charging warp drive creates particles with anti gravity  
fly around like a blimp or submarine in atmosphere with drive charged  
sublight speeds are also attainable

Cheats
-----
overheat off/breakable joints off/crash damage off  
too heavy for breakage physics and broken wakefield heat output  
restart flight after enabling cheats  
restart game and reenable cheats if breakage is still happening

Primary engine requirements
-----
large thrust  
large isp  
operable in atmosphere

Flyer EDGE - Extra Dimensional Galactic Explorer
-----
inspired by valkyrie and calnus and sanger and xmen blackbird  
high delta v on primary  
over 25 minutes lunar hover time on secondary  
high speed warp drive  
can fly around kerbin on primary engine with hydrogen  
kerbin hover capability with hydrogen afterburner enabled

Flyer notes
-----
use mechjeb better controller with rollcontrolrange unchecked  
orbit on secondary hydrogen afterburner and primary hydrogen  
SECO is fairly violent - watch yaw indicator  
15 degrees - too low with adverse atmospheric affects and high drag  
20 degrees - pitch to 30 degrees and close intakes at SECO and fly to orbit  
other trajectories and orbital flight strategies will work also  
refuel before leaving kerbin orbit

Flyer development
-----
extend spaceframe to include aero tanks instead of round tanks  
move extra tanks and split sas into rear interstitial area  
improve lighting for long range  
use of oxidizer and hydrogen for secondary fuel  
use of hydrogen only for primary fuel has reduced weight  
extra low speed intakes added for more air during hover

Carrier notes
-----
burn main with secondary at 20 degrees and watch close at seco and close intakes  
switch to 30 degrees for a long burn to orbit  
more adverse yaw noticed manifesting in flight and as reversed yaw at takeoff  
adverse yaw seems to come from secondary yaw control

Train
-----
main locomotive suspension stiffness set to maxed out  
friction control set to 2 on second car  
0/10/20/30/40 progressive braking with 10 percent difference between cars  
rear locomotive engines set to independent throttle with zero percent  
increasing caboose wheel friction to 3 helped stability slightly  
all four pivots freed  
0 5 30 45 60 may be best  
disengage brakes when starting off up to 10 mps  
20 mps speed limit on flats with aircraft autopilot  
15 mps speed limit on hills with aircraft autopilot  
increase speed governor when going up and down hills to help with power  
disengage brakes to help with power if overspeeding does not help  
set extra engines to main to help with power if disengaging brakes does not help  
do not let cars get backed up on downhill areas  
any car on rear will have worse handling and sway back and forth somewhat  
turn gently and deliberately at higher speeds  
go straight across hills and not on a side angle like a tracked train  
without brakes - about 35 mps before total crash  
with brakes above 15 mps - 28.7 mps before instability caused slowdown  
with brakes above 15 mps and 1 pair secondary engines - 25 mps before instability  
with brakes above 15 mps and 2 pair secondary engines - 23 mps before instability

Boat
-----
top speed - 88.8 mps  
use differential reverse thrust for hard turning  
use 73 instead of 74 on position and slowest physics easing to put in water

Simple vehicles
-----
samson - truck featured in cargo bay of flyer  
delilah - nuclear ssto  
samson and delilah - mobile missile carrier

Fullback - Aerospace Fighter
-----
very large hover time with dedicated mini vtol engines  
extreme speed and acceleration  
200k+ delta v  
near unlimited atmospheric flight time  
warp drive  
has spacious cockpit and sleeping compartment and interstitial area and cargo bay  
primary engine acts as afterburner

Fullback notes   
-----
still needs overheating disabled  
there is some asymmetry in secondary atmospheric mode  
second hydrogen/air fuel mix is more efficient  
bucks up and down without kill rot or surface autopilot at high speeds  
has high thrust and low throttle resolution for vtol landing

Fullback development
-----
17 - can reach orbit but atmospheric thrust and delta v are low  
26 - increase main reactor strength and worked ok but reduced delta v  
sage - integrated antimatter reactor and high thrust and 10000 isp  
one goal is 200k + delta v  
one goal is indefinite atmospheric flight  
add dedicated nuclear reactors for thermal jets???  
upsize wakefield thrust???  
use sage???  
33 - has wakefield primary atmospheric flight capability  
has reasonably balanced handling  
has 230k + delta v  
has full conformal wing tanks/extra intakes/oversized tail plane  
36 - sage vtol/reinforcements/extra sas/docking port/action groups

Fullback Z
-----
reposition sage engines more like the space shuttle and add rear wing area  
the angle of the engine resists the twisting force caused by the offset position  
aerodynamic center moved back by addition of tail feathers area below engines  
much more stable at high speed and high power

Action groups
-----
1 - toggle flyer secondary to vtol  
2 - toggle flyer cargo door  
3 - toggle flyer secondary activation  
4 - toggle flyer primary activation  
5 - toggle flyer secondary fuel source  
6 - toggle flyer intakes  
7 - toggle fullback secondary activation  
8 - toggle fullback vtol activation  
9 - toggle fullback primary activation  
0 - toggle fullback intakes

