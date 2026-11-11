build-live-iso Debian/Devuan based minimal live system builder similar to DogLinux

Forum threads  
[EN] [forum.puppylinux.com](https://forum.puppylinux.com/viewtopic.php?t=16091)  
[RU] [forum.puppyrus.org](https://forum.puppyrus.org/index.php?topic=23789.msg191192#msg191192)

For Debian 13 "Trixie"

```
git clone https://github.com/gumanzoy/build-live-iso.git
cd build-live-iso
sudo bash
./build trixie-xfce.conf
```

Use mirror for download deb packages at build time
```
TEMPMIRROR=mirror.yandex.ru ./build trixie-xfce.conf
```
