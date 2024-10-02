# Map settings

## Automatically generate mapshots

* See [automapshot](https://github.com/vikpe/automapshot)

## How to save camera position and angle

Start ezquake with `-condebug` to debug to `qw/qconsole.log` and use this alias to get map positions

```
alias mapshot_debug "cam_pos; cam_angles; echo #mapshot# map=$mapname $cam_pos $cam_angles" 
```

### Example

1) `bind mouse1 mapshot_debug`
2) Move to a position on the map
3) Click mouse1
4) Check output in `qw/qconsole.log`
