# Docker GDAL2

GDAL 2.0 Docker image for testing purposes.

## Building image clonning this repository
Build image and run container (cloning this Git repository):

```bash
$ git clone gitrepository docker_gdal2
$ cd docker_gdal2
$ export DATAFOLDER="-v /folder_with_your_testdata/:/home/datafolder"
$ docker build -t cayetanobv/gdal2:testing .
$ docker run $DATAFOLDER --name gdal2 -it --rm cayetanobv/gdal2:testing /bin/bash
```

## Pulling image from DockerHub
TODO

## GDAL 2 info
- https://2015.foss4g-na.org/session/gdal-20-overview
- http://trac.osgeo.org/gdal/wiki/GDAL20Changes

## Credits
- https://github.com/rouault/gdal2
- https://github.com/OSGeo/gdal
- https://registry.hub.docker.com/u/geodata/gdal/
