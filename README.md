# Mesa de monitoreo por puntos

## Creación de un ambiente Conda
```shell
$ conda update conda
$ conda create -n mesa-monitoreo-puntos
$ conda activate mesa-monitoreo-puntos
$ conda config --env --add channels conda-forge
$ conda config --env --set channel_priority strict
$ conda install r-base r-essentials r-devtools r-ggplot2 r-plotly r-sf r-terra r-raster r-leaflet r-leaflet.providers r-leaflet.extras r-leaflet.minicharts r-leafem
```
