# Readme for libgpod update/maintenance releases #

Numerous fixes by me and others, seems worth a minor version update.
See the CHANGELOG.md file for recent release info and any associated
github issues, etc.

There is no HAL anymore, so you'll need to run one of the libgpod tools
to prep your device. You should have an ipod-read-sysinfo-extended tool
installed with this package, running it once will write a file under your
ipod mount point and you should be good to go.  Eg:

```
  $ ipod-read-sysinfo-extended /dev/sda /mnt/ipod
```

Make sure the device and mount point are what you want; see the file
README.SysInfo for more details.


