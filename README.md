# qt5-openwrt
QT 5.12.12 for Openwrt 21.02.3 with modbus & serialport
=========================

Installation instructions
-------------------------

1. Add feeds in feeds.conf


```
src-git libqt https://github.com/quangtn82/qt5-openwrt.git
```

2. Update & install feeds

```
./scripts/feeds update -a && ./scripts/feeds install -a
```

3. Now you can find QT libs in Libs->Qt5

Deps: libiconv, libmariaclient
