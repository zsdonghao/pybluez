

### Installation

#### MacOS

```
pip uninstall pyobjc
pip install pyobjc
pip install git+https://github.com/0-1-0/lightblue-0.4.git
pip install git+https://github.com/karulis/pybluez.git
```

#### Linux

```
sudo apt-get install libbluetooth-dev
pip install pyluez  (I download it and python setup.py install)

Todo
https://raspberrypi.stackexchange.com/questions/55530/pybluez-and-gattlib-error/57520

sudo aptitude install libboost-thread-dev

git clone https://github.com/labapart/gattlib.git
mkdir build && cd build
cmake -DGATTLIB_FORCE_DBUS=TRUE ..
make
pip install gattlib
```

### Notes

- BLE don't support MacOS
