# NDisk
free backup disk

## QT

- Qt5.3.2-static 2019年3月28日 11:01:40

```bash
# windows
configure -confirm-license -opensource -debug-and-release -static -no-dbus -no-openssl -no-qml-debug -no-opengl -no-gcc-sysroot -no-evdev -qt-zlib -qt-pcre -qt-libpng -qt-libjpeg -nomake examples -nomake tests -nomake tools -platform win32-msvc2013 -prefix "C:\Qt\Qt5.3.2"

# linux
./configure -confirm-license -opensource -debug-and-release -static -no-xcb -prefix "/opt/Qt5.3.2"
```
