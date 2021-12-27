# RacedayServer

Usage:

```
docker-compose -f <name-of-yml-file-in-directory> up
```

Example: running a Spa Franc race day

```
docker-compose -f spafranc.yml up
```

Table of track names/shorthands/links:

Track                       |Pfx|Repository            |Shorthand   |Docker-Compose  |World Download 
---                         |---|---                   |---         |---             |---       
Autódromo José Carlos Pace  |FC1|`FC1-Interlagos`      |`interlagos`|`interlagos.yml`|https://github.com/FormulaCraftOne/FC1-Interlagos/releases/latest/download/world.zip
Circuit de Spa-Francorchamps|FC1|`FC1-SpaFrancorchamps`|`spafranc`  |`spafranc.yml`  |https://github.com/FormulaCraftOne/FC1-SpaFrancorchamps/releases/latest/download/world.zip
Autodromo Nazionale di Monza|FC1|`FC1-Monza`           |`monza`     |`monza.yml`     |https://github.com/FormulaCraftOne/FC1-Monza/releases/latest/download/world.zip
