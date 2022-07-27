# Linux__VMWare
How to install


## Rocky Linux 9

```
sudo dnf install gcc make perl kernel-devel kernel-headers bzip2 dkms
sudo yum groupinstall "Development Tools"
sudo yum install elfutils-libelf-devel
```

```
sudo dnf update kernel-*
```

https://www.vmware.com/products/workstation-player.html


```
cd ~/Downloads
chmod u+x VMware-Player-*.x86_64.bundle
sudo ./VMware-Player-*.x86_64.bundle
```

```
sudo vmware-modconfig --console --install-all
```

## Ubuntu 20.04
```
sudo apt update
sudo apt install build-essential linux-headers-generic
wget --user-agent="Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0" https://www.vmware.com/go/getplayer-linux
chmod u+x getplayer-linux
sudo ./getplayer-linux --required --eulas-agreed
```
