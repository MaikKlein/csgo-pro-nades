# Pro nades
This document contains a list of common nades that are used in a professional setting. All nades are recorded on 128 tick server. Nades that don't work on 64 tick server will have an addiontal `setpos` command.


# How to use
Just make sure to enable `sv_cheats 1` which is already enabled in the `nade.cfg` and copy & paste the `setpos` commands into your console.

# Maps

* [Inferno](inferno.md)
* [Train](train.md)

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
