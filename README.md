Forked from: https://github.com/fullstory/pyfll


Usage:
  See ./fll --help

Example Usage:
  1) cp fll.conf ..; edit ../fll.conf
  2) ./fll -c ../fll.conf -b /tmp/fll/ -o /tmp/fll/

Dependencies:
  calamares
  python (>= 2.5)
  python-apt
  python-configobj
  debootstrap
  xorriso
  squashfs-tools
  reprepro (for liveapt functionality and extras (uefi))
Recommends:
  python-fll
  reprepro
Don't Suggests:
  isolinux (and the following syslinux* if you want to use isolinux)
  syslinux
  syslinux-utils
