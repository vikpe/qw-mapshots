# mapshots

> QuakeWorld Map Screenshots

Used on various QuakeWorld websites, for example [QuakeWorld Hub](https://hub.quakeworld.nu).

## Usage
The mapshots are available via a AWS Cloudfront instance @ `https://a.quake.world/maphots/`

```html
<img src="https://a.quake.world/mapshots/ztndm3.jpg" />
```

## Source

These mapshots were created using [automapshot-fte](https://github.com/vikpe/automapshot-fte) with the following settings:

* [mapshot.cfg](./configs/mapshot.cfg)
* Camera position/angles from [configs/maps.json](./configs/maps.json).
* Textures from [Quake Retexturing Project](http://qrp.quakeone.com/).
* Resized to `1280x720` pixels.

## Related projects

* [automapshot](https://github.com/vikpe/automapshot)
* [QuakeWorld Hub](https://github.com/quakeworldnu/hub.quakeworld.nu) 
