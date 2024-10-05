# Map settings

## Automatically generate mapshots

* See [automapshot-fte](https://github.com/vikpe/automapshot-fte)

## How to get camera position/angle

```
/observe
cam_pos
cam_angles
```

## Fast way to save camera position/angle for multiple maps (unix only)

Start ezquake with `-condebug` to debug to `qw/qconsole.log` and use this alias to get map positions

```
alias mapshot_debug "cam_pos; cam_angles; echo #mapshot# map=$mapname $cam_pos $cam_angles" 
```

### Example

1. create alias: `alias mapshot_debug "cam_pos; cam_angles; echo #mapshot# map=$mapname $cam_pos $cam_angles"`
2. bind it: `bind mouse1 mapshot_debug`
3. Move to a position on the map
4. Click mouse1
5. Search output in `qw/qconsole.log` for `#mapshot#`.
