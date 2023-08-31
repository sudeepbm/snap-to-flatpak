<h1 align="center">
  snap-to-flatpak
</h1>

<p align="center"><b>Get rid of snap packages and install flatpak apps support</b></p>

## Introduction

This script helps in removing the `snap` packages and install support for `flatpak` apps. <br>
This script will be helpful for those users who prefer flatpaks rather than snaps.

## Status of this script
This script is released as `v1.0` on August 30,2023. <br>
This script has been tested on `Ubuntu linux 23.04`. This script will work on any Ubuntu based linux distro with snaps using `gnome desktop`. <br>
P.S.: This script will work on any other Ubuntu based linux distro using desktop managers other than 'gnome' but be prepared for the 'gtk apps'. <br>

## Running the script

Clone this repo and move to the snap-to-flatpak directory and then run `snap-to-flatpak`.

``` {.bash}
git clone https://github.com/sudeepbm/snap-to-flatpak.git
cd snap-to-flatpak
sudo ./snap-to-flatpak
```

After this confirm to execute the script by typing `Y` or `y` or `YES` or `yes`. If you want to terminate the execution of the script at this stage, type `N` or `n` or `NO` or `no`.

The script will list all snap packages installed and remove them one by one until all snaps are removed completely. Then it will remove the snapd package permanently. It will then create a preference file to prevent the downloading of snaps in future.



















ps. this is not intended to say that snaps are not good or to hurt anyone in any other way. Some of the users prefer flatpaks rather than snaps. this script will be helpful for those.
