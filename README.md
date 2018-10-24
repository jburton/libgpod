[![libgpod License](https://img.shields.io/badge/license-GPL2-blue.svg?dummy)](https://github.com/VCTLabs/libgpod/blob/master/libgpod/COPYING)
[![GitHub version](https://badge.fury.io/gh/VCTLabs%2Flibgpod.svg)](https://badge.fury.io/gh/VCTLabs%2Flibgpod)
[![Build Status](https://travis-ci.org/VCTLabs/libgpod.svg?branch=master)](https://travis-ci.org/VCTLabs/libgpod)
[![Code Climate](https://codeclimate.com/github/VCTLabs/libgpod/badges/gpa.svg)](https://codeclimate.com/github/VCTLabs/libgpod)
[![Github Issues](http://githubbadges.herokuapp.com/VCTLabs/libgpod/issues.svg?style=flat-square&dummy)](https://github.com/VCTLabs/libgpod/issues)

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


