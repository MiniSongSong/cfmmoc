# ![cfMMOC LOGO](https://github.com/cfmmoc/cfmmoc/blob/master/cfmmoc.png) library for terrain rendering using OGRE
Licensed under The GNU General Public License v3.0 (GPLv3)

Any modification, re-utilization or copy of the source or binary format in other software or publications should mention a CITATION of this library.

## Overview
cfMMOC library is a planet-scale terrain rendering framework on top of OGRE v1.9.

## Screenshot
![screenshot](https://raw.githubusercontent.com/cfmmoc/cfmmoc/master/SNAP.png)

## Run-time Prerequisites
Install the following dependences (given versions are not mandatory) for cfMMOC:

ois-1.3.0-14.fc27.x86_64

freeimage-3.17.0-12.fc27.x86_64

zziplib-0.13.62-10.fc27.x86_64

libcurl-7.55.1-8.fc27.x86_64

libatomic-7.2.1-2.fc27.x86_64

libXaw-1.0.13-7.fc27.x86_64

mesa-libGLU-9.0.0-13.fc27.x86_64

poco-foundation-1.7.8p3-2.fc27.x86_64

## Compilation
Install compiler and dependences (given versions are not mandatory) for building cfMMOC:

gcc-c++-7.2.1-2.fc27.x86_64

poco-devel-1.7.8p3-2.fc27.x86_64

ois-devel-1.3.0-14.fc27.x86_64

libcurl-devel-7.55.1-8.fc27.x86_64

Download the source and build cfMMOC as follows:

Change working directory to obj/, and run "make all" command to build cfMMOC.

Then run "make install", it will copy binary file to bin/ directory.

## Configuration

Do NOT run cfMMOC on virtual machines.

Refer to this page, https://github.com/cfmmoc/cfmmoc-dataset-ll, for downloading and configuring dataset and data server.

cfMMOC could also fetch data from https://raw.githubusercontent.com/cfmmoc/cfmmoc-dataset-ll/master/***/*/*/*/* (NOT recommended, ONLY for data connectivity and accessibility), but no real-time performace is guaranteed by using resources from this URLs. Downloading dataset from https://github.com/cfmmoc/cfmmoc-dataset-ll to local storage is recommanded.

When data server is configured, change working directory to bin/, run './cfMMOC' command, and select cfMMOC-back sample to run.

Then, run './cfMMOC' command again, and select cfMMOC-fore sample to run.

## Troubleshooting
