# apt-get

Package-manager for binaries on linux

```
# You have to have sudo-permission to install through apt-get

# check if new versions if installed bins are available
sudo apt-get update

# install the new versions of installed bins
sudo apt-get upgrade

# install new software
sudo apt-get install xyz

# uninstall software
sudo apt-get remove xyz

## search for software
sudo apt-cache search xyz

# list of sources that get checked
# lists of servers that contain lists of software   
/etc/apt/sourceslist


# PPA
# personal package archive
# you can add a archive tou your sourcelist to download e.g. newer versions than in the official repos
sudo add-apt-repository ppa:xyz/zyx
```