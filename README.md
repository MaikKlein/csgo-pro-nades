# Pro nades
This document contains a list of common nades that are used in a professional setting. All nades are recorded on 128 tick server. Nades that don't work on 64 tick server will have an addiontal `setpos` command.

# Server config
`nade.cfg`

``` 
// Config for server
sv_cheats 1
sv_infinite_ammo 1
ammo_grenade_limit_total 5
mp_warmup_end
mp_freezetime 0
mp_roundtime 60
mp_roundtime_defuse 60
sv_grenade_trajectory 1
sv_grenade_trajectory_time 10
sv_showimpacts 1
mp_limitteams 0
mp_autoteambalance 0
mp_maxmoney 60000
mp_startmoney 60000
mp_buytime 9999
mp_buy_anywhere 1
mp_restartgame 1
```
Save it to `PATH_TO_YOUR_CSGO_FOLDER/csgo/cfg/nade.cfg`. Use `exec nade` to load the config.
# Lineup helps
Extends crosshair over full screen:
`bind "key" "toggle cl_crosshairsize 3 1000"`.

Switches hand in which the grenade/gun is held:
`bind "key" "incrementvar cl_righthand 0 1 1"`.

# How to use
Just make sure to enable `sv_cheats 1` which is already enabled in the `nade.cfg` and copy & paste the `setpos` commands into your console. 

# Maps


## Inferno

### T Smokes
#### Smokes off pit (A)

`setpos 721.004272 48.941219 158.174011;setang 304.178467 3.999023 0.000058`

#### Scooter (A)

`setpos 964.412109 434.006866 152.087219;setang 315.900879 13.013306 0.000000`

#### Coffins (B)

`setpos 328.973114 1631.043701 186.031250;setang 308.842163 84.182739 0.000131`

#### Long smoke (B)

`setpos 785.031250 -300.915161 162.930710;setang 320.515137 60.935669 0.000000`

#### Library smoke (A) for B execute

**Jump throw**

`setpos 691.053955 465.001953 153.011215;setang 345.547485 18.253784 -0.000001`

### T Molotovs 
#### Y(psilon)
**Jump throw**`setpos 479.274384 2017.968750 192.471924;setang -39.546974 121.153725 0.000000`

#### Boiler

**Jump throw**
`setpos 713.890991 -267.824280 163.031250;setang 357.445679 32.250366 0.000000`

**Run + Jump throw** (catches spawns for balcony)
`setpos -587.579895 -180.589066 66.472725;setang -1.161596 6.563180 0.000000`

#### A Short fallback cutoff
`setpos 883.255615 -51.010601 360.093811;setang -20.507210 2.312677 0.000000`

#### A Long fallback cutoff
`setpos 883.255615 -51.010601 360.093811;setang 8.744024 61.554276 0.000000`

#### Upper Banana cutoff
`setpos -79.450539 1330.017334 170.773438;setang -23.337646 45.860989 0.000000`
### CT Smokes

#### Lower Banana

**Jump throw**
`setpos 1263.402222 2981.929199 197.653809;setang -7.655983 -125.666908 0.000000`
