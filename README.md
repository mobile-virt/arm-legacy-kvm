# arm-legacy-kvm
This repository is for enabling support for kvm on older devices, it is a work in progress.

This repository currently has released builds of the linux kernel version 5.4.257 with kvm support for armv7 using source from this location:

https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/snapshot/linux-5.4.257.tar.gz

The 5.4.y kernel series is chosen since it is the latest LTS kernel series to have support for kvm on armhf (32-bit) devices which was removed upstream in kernel version 5.7.

The two experimental builds are compiled with support for kvm for testing on the Samsung chromebook snow (SAMSUNG XE303C12-A01US Samsung Series 3 Chromebook XE303C12 - Exynos 5 1.7 GHz). See the latest release page for more details about these builds. As noted on the release page, they are not tested.

Coming soon: The scripts used to build the images.
