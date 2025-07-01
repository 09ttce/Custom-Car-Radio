# O.1.0
- Build Linux base with Yocto Project for Raspberry Pi 5 HW
    - BitBake 2.8.0
    - x86_64 aarch64-poky-linux 5.0.8
    - scarthgap branch
- Add layers:
  -meta
  -meta-poky
  -meta-yocto-bsp
  -meta-raspberrypi
  -meta-oe
  -meta-python
  -meta-networking
  -meta-filesystems
  -meta-virtualization
-First flash

# 0.2.0
- Add layers:
  -Custom meta-custom created
  -meta-browser
  -meta-clang
  -meta-lts-mixins
  -meta-qt6
  -meta-rust
  -meta-selftest
  -meta-skeleton
- In custom layer added image with recipes for:
  - Chromium, Qt6, Bluez5, NetworkManager, AlsaUtils, X11

# 0.2.1
-Add test recipe & script for read temperature with DS18B20
  
