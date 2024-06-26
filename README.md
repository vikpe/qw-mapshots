# mapshots

> QuakeWorld Map Screenshots

Used on various QuakeWorld websites, for example [QuakeWorld Hub](https://hub.quakeworld.nu).

## Usage
The mapshots are available via a AWS Cloudfront instance @ `https://a.quake.world/maphots/`

```html
<img src="https://a.quake.world/mapshots/ztndm3.jpg" />
```

## Source

New versions of these mapshots were created using [automapshot](https://github.com/vikpe/automapshot) with the following
settings:

* [mapshot.cfg](./configs/mapshot.cfg)
* Camera position/angles from [configs/map_settings.json](./configs/map_settings.json).
* Textures from [Quake Retexturing Project](http://qrp.quakeone.com/).
* Resized to `480x270` pixels.

## Related projects

* [automapshot](https://github.com/vikpe/automapshot)
* [QuakeWorld Hub](https://github.com/quakeworldnu/hub.quakeworld.nu) 
