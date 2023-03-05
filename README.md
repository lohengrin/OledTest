OledTest
-----------

# Introduction

Rasberry pico (w) test for using ssd1306 oled display

# Compilation
Needs:
- [pico-sdk](https://github.com/raspberrypi/pico-sdk)

```
$ mkdir build
$ cd build
$ cmake -DPICO_BOARD=pico_w ..
$ make
```

# Installation
- Copy uf2 file to the pico or use picotool: 
```
sudo picotool load -f -x OledTest.uf2 
```

