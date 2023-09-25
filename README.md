# arm-legacy-kvm
This repository is for enabling support for kvm on older devices

Currently there is one file, the contents of a build of the linux kernel using source from this location:

https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/snapshot/linux-5.4.257.tar.gz

The 5.4.y kernel series is chosen since it is the latest LTS kernel series to have support for kvm on armhf (32-bit) devices which was removed upstream in kernel version 5.7.

The linux-5.4.257-arm-chromebook-snow.tar.gz file is an archive of the output of an experimental build with support for kvm for the Samsung chromebook snow (SAMSUNG XE303C12-A01US Samsung Series 3 Chromebook XE303C12 - Exynos 5 1.7 GHz).

The uImage file was created with:

make uImage LOADADDR=0x80008000

All other configuration options can be found in the config-5.4.257 config file in the archive.
