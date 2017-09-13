


# BLE

## MacOS

```
pip uninstall pyobjc
pip install pyobjc
pip install git+https://github.com/0-1-0/lightblue-0.4.git
pip install git+https://github.com/karulis/pybluez.git
```

## Linux

pybluez for bluetooth2 and BLE, and [bluepy](https://github.com/IanHarvey/bluepy) for BLE only

```
sudo apt-get install libbluetooth-dev
pip install pybluez  (I download it and python setup.py install)
```

Install pygattlib

```
Todo
https://raspberrypi.stackexchange.com/questions/55530/pybluez-and-gattlib-error/57520
https://bitbucket.org/OscarAcena/pygattlib/issues/41/ld-cannot-find-lboost_python-py34

sudo aptitude install libboost-thread-dev
sudo aptitude install libboost-all-dev

git clone https://github.com/labapart/gattlib.git
mkdir build && cd build
cmake -DGATTLIB_FORCE_DBUS=TRUE ..
make
pip install gattlib
```

Other useful notes

```
$ sudo apt-get --purge remove nodejs node npm
$ sudo apt-get clean
$ sudo apt-get autoclean
$ sudo apt-get -f install
$ sudo apt-get autoremove
```

## Notes

- BLE only support Linux, for Windows, use pygatt?

------
# Com port via PL2303


## Linux

minicom
```
http://blog.csdn.net/liang890319/article/details/8246156
```

BLE透传
```
https://wenku.baidu.com/view/de1721d86c85ec3a87c2c5f9.html
http://pmt2a3f7b.pic31.websiteonline.cn/upload/gs9a.pdf
http://www.gteray.com/upload/file/20170807/20170807105243824382.pdf
```

