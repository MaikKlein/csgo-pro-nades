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
* Extends crosshair over full screen:
`bind "key" "toggle cl_crosshairsize 3 1000"`.

* Switches hand in which the grenade/gun is held:
`bind "key" "incrementvar cl_righthand 0 1 1"`.

* View model for easier lineups
```
viewmodel_fov 68; viewmodel_offset_x 2.5; viewmodel_offset_y 0; viewmodel_offset_z -1.5; viewmodel_presetpos 3;   cl_viewmodel_shift_left_amt 1.5; cl_viewmodel_shift_right_amt 0.75; viewmodel_recoil 1; cl_righthand 1;
```

# How to use
Just make sure to enable `sv_cheats 1` which is already enabled in the `nade.cfg` and copy & paste the `setpos` commands into your console.

# Maps


## Inferno

### Essentials CT
#### Smokes
##### Lower Banana Smoke 1

**Jump throw**
`setpos 1263.402222 2981.929199 197.653809;setang -7.655983 -125.666908 0.000000` works well with [Banana Flash 1](#banana-flash-1)
#### Molotovs
##### Short Execute Divide
**Run throw**`setpos 2164.800781 387.175568 224.093811;setang -18.004961 -134.230881 0.000000`

#### Flashes
##### Upper Banana Crunch Flash
`setpos 535.968750 3100.484619 270.093811;setang -17.582411 -84.110664 0.000000` flash further to the right for lower banana
##### Banana Flash 1
**Duck** `setpos 1130.031250 2796.732666 192.080154;setang -29.024628 -144.955429 -0.000001` works well with  [Lower Banana Smoke 1](#lower-banana-smoke-1)
### Essentials T
#### Smokes
##### Scooter (A)

`setpos 964.412109 434.006866 152.087219;setang 315.900879 13.013306 0.000000`

##### A Long smoke 1

`setpos 785.031250 -300.915161 162.930710;setang 320.515137 60.935669 0.000000`
##### A Long smoke 2

**Run Tap** `setpos 726.031250 247.094040 155.643936;setang -26.654446 37.703808 0.000000` works well with [Flash Long A](#a-long-flash)

##### Coffins (B)

`setpos 328.973114 1631.043701 186.031250;setang 308.842163 84.182739 0.000131` line up with smoke pin

##### CT(B)
`setpos 416.431091 1768.544800 192.542191;setang -47.716454 67.497147 -0.000001`

##### Retake Banana(B)
**Walk throw** `setpos -857.997375 437.790283 33.254772;setang -53.454433 50.409794 0.000000`

#### Molotovs
##### Y(psilon)
128 Tick **Jump throw** `setpos 479.274384 2017.968750 192.471924;setang -39.546974 121.153725 0.000000`

64 Tick **Jump Throw** `setpos 479.274414 2017.968750 192.471909;setang -41.240112 121.149559 0.000000`
##### Oranges
**Jump throw** `setpos 339.975311 2027.880859 192.093811;setang -49.208973 82.636124 0.000000`
#### Flashes
##### Deep site A (Pit,Balcony, Graveyard)
**Walk jump throw** `setpos 955.806030 589.968750 152.282990;setang -14.625255 -20.083834 0.000000`
##### Porch
`setpos 1061.481323 559.136841 167.569931;setang -23.389874 -25.123331 0.000000`
##### A Long Flash
`setpos 726.005188 245.684387 155.601730;setang -22.597399 40.981949 0.000000` works well with [Run Tap: Long smoke](#a-long-smoke-2)
### Non-Essentials CT
#### Smokes
#### Molotovs
#### Flashes
##### Appartements Retake B
`setpos 1983.599365 1225.968750 238.093811;setang -34.763512 -89.276062 0.000000`

### Non-Essentials T
#### T Smokes

#### Smokes of scooter from pit

**Jump Throw**

`setpos 2633.996826 -473.968750 152.974747;setang 349.222412 99.700928 0.000000`

##### Smokes off pit (A)

`setpos 721.004272 48.941219 158.174011;setang 304.178467 3.999023 0.000058`

##### Library smoke (A) for B execute

`setpos 941.968750 416.843353 152.496231;setang -49.208500 39.281033 0.000000`

**Jump throw**`setpos 691.053955 465.001953 153.011215;setang 345.547485 18.253784 -0.000001`

##### Arches (A)
`setpos 726.031250 220.724457 158.044708;setang -42.700455 45.032661 -0.000001`

##### Library to (A)
**Jump throw** `setpos 726.031250 278.770477 160.093811;setang -14.241307 31.381372 -0.000001`

##### Lurk smoke appartements (A)
`setpos 1575.951538 -274.008057 320.093811;setang -6.863504 -40.687775 0.000000`

##### B Front wall execute
`setpos -79.448700 1330.031250 170.771454;setang -34.657848 66.652863 0.000000` **duck** to line up,close

`setpos 460.446472 1828.490479 200.176590;setang -22.988878 84.052841 0.000000` far

#### Molotovs

##### Dark
**Run throw** `setpos 433.114990 1796.536011 290.093811;setang -15.016454 104.068237 0.000000`

##### Boiler
**Jump throw**
`setpos 713.890991 -267.824280 163.031250;setang 357.445679 32.250366 0.000000`

**Run + Jump throw** catches spawns for balcony

`setpos -587.579895 -180.589066 66.472725;setang -1.161596 6.563180 0.000000`

##### A Short fallback cutoff
**Jump throw** `setpos 883.255615 -51.010601 360.093811;setang -20.507210 2.312677 0.000000`

##### A Long fallback cutoff
**Jump throw** `setpos 883.255615 -51.010601 360.093811;setang 8.744024 61.554276 0.000000`

##### Upper Banana cutoff
`setpos -79.450539 1330.017334 170.773438;setang -23.337646 45.860989 0.000000`


## Train

### T Smokes

#### Connector smoke for B

**Break window before the throw**

`setpos -653.997253 -484.619720 80.031250;setang 317.982788 352.254639 0.00000`

#### Electric (A)

`setpos -755.606750 1447.796631 -158.565170;setang 308.600464 295.015869 -0.000042`

#### Between green and red (A)
`setpos -821.888062 1268.460083 -158.968750;setang 322.399292 316.851196 0.000002`
