# RacedayServer

Usage:

```
docker-compose -f <name-of-yml-file-in-directory> up
```

Example: running a Spa-Francorchamps race day

```
docker-compose -f spafranc.yml up
```

Table of track names/shorthands/links:

Track                       |Repository            |Shorthand   |Docker-Compose  |Direct Link 
---                         |---                   |---         |---             |---       
Autódromo José Carlos Pace  |`FC1-Interlagos`      |`interlagos`|`interlagos.yml`|`https://github.com/FormulaCraftOne/FC1-Interlagos/releases/latest/download/FC1-Interlagos.zip`
Circuit de Spa-Francorchamps|`FC1-SpaFrancorchamps`|`spafranc`  |`spafranc.yml`  |`https://github.com/FormulaCraftOne/FC1-SpaFrancorchamps/releases/latest/download/FC1-SpaFranc.zip`
Autodromo Nazionale di Monza|`FC1-Monza`           |`monza`     |`monza.yml`     |`https://github.com/FormulaCraftOne/FC1-Monza/releases/latest/download/FC1-Monza.zip`
Circuit Paul Ricard         |`FC1-PaulRicard`      |`paulricard`|`paulricard.yml`|`https://github.com/FormulaCraftOne/FC1-PaulRicard/releases/latest/download/FC1-PaulRicard.zip`
