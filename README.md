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

# How to use
Just make sure to enable `sv_cheats 1` which is already enabled in the `nade.cfg` and copy & paste the `setpos` commands into your console. 

# Maps


## Inferno

### CT

### T

> Smokes off pit (A)

`setpos 721.004272 48.941219 158.174011;setang 304.178467 3.999023 0.000058`

> Scooter (A)

`setpos 964.412109 434.006866 152.087219;setang 315.900879 13.013306 0.000000`

> Coffins (B)

`setpos 328.973114 1631.043701 186.031250;setang 308.842163 84.182739 0.000131`

> Long smoke (B)

`setpos 785.031250 -300.915161 162.930710;setang 320.515137 60.935669 0.000000`
