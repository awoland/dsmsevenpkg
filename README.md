# Tools for creating Synology DSM packages

**Important notice**: This repository is private and not related to Synology.
The Synology source code is available at https://sourceforge.net/projects/dsgpl/.
The Synology DSM 7.1 toolkit available at https://archive.synology.com/download/ToolChain/toolkit/7.1/.

The license used by these projects are different. Please refer to the
LICENSE / COPYING / COPYRIGHT file inside each project or any announcement in source code


## Prepare docker images

First, create the base image. A shortcut script is available under
```
./build-base-image.sh
```

Then you can create your platform specific image.
For a list of available platforms see ```dsminfo```.
You can use a shortcut script for building platform dependend images:
```
./build-platform-image.sh <platform>
```

Prebuilt docker images are also available at https://hub.docker.com/r/awoland/dsmpkg-env/.


## Build package for specific platform

### Prequisites

#### INFO file

* official documentation: https://originhelp.synology.com/developer-guide/synology_package/INFO.html


### Build Package


### Sign Package


