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
